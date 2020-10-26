<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> <script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: { skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'], inlineMath: [['$','$']] } }); </script> 

## Kriging and Cokriging


Recently I have found that the R package gstat gives good performance on missing data imputation. So I have revisited the concepts of kriging and cokriging. Below is my understanding:


The simplest method is kriging:

\begin{equation}
    Z^e(s_0) = m + \sum^N_{n = 1} \lambda_n (Z(s_n) - m),
\end{equation}

where $s_0$ is a vector of the location where unobserved variable $Z$ will be predicted, $m$ is the mean of the dataset, $\lambda_n$ is a weight of an observation $n$. $s_n$ is a vector of the location where an observed $Z$ is placed on a spatio-temporal plane around $s_0$, and $N$ is the number of observation used for Kriging. 

In kriging, the weight $\lambda_n$ is calculated based on the spatial dependence between two locations. The dependency for a given spatial lag vector $h$ is captured by half of covariance, called variogram $\gamma(h)$, where Euclidean distance between the observed data at any pair of locations is used. 

\begin{equation}
    \gamma(h) = \frac{1}{2} Cov(Z(s_n), Z(s_n+h)),
\end{equation}

For the estimated variogram model, the covariances are calculated based on the lag vector $h$ between observed locations and between an observed and unobserved location. The logic here is to use observed locations to estimate variogram, after that, we can get an estimated variogram for any given location since $h$ is the lag between two locations.


 Next, the weights of Kriging model are assigned by multiplying the inverse of the former covariance matrix with the latter covariance matrix.
 
 $    \begin{bmatrix}
   \lambda_1       \\[0.3em]
   \vdots \\[0.3em]
   \lambda_N
     \end{bmatrix}  =  \begin{pmatrix}
  c_{s_1,s_1}  & \cdots & c_{s_1,s_N} \\
  \vdots  & \ddots & \vdots  \\
  c_{s_N,s_1}  & \cdots & c_{s_N,s_N} 
 \end{pmatrix} ^ {-1}      \begin{bmatrix}
  c_{s_1,s_0}       \\[0.3em]
   \vdots \\[0.3em]
  c_{s_1,s_N} 
     \end{bmatrix},$
 
 where $c_{s_x,s_y} = Cov(Z(s_x), Z(s_y))$. $c_{s_x,s_0}$ can be computed by estimated variogram. Kriging can be viewed as a weighted $N$-nearest neighbor. The weights are determined by the variogram, variogram is a function on distance between two locations.
 
Kriging methods only use data available at the target location. Cokriging methods are used to take advantage of the covariance between two or more regionalized variables that are related. That means $Z(s_n)$ becomes a vector, whose dimension equals to the number of variables. The variogram is estimated by covariance between more variables.

Cokriging can be viewed as the following function:

\begin{equation}
    Z^e(s_0) = f(Z(s_1, s_2, \cdots, s_N), h_{s_0}(s_1, s_2, \cdots, s_N))
    \label{cok_eq}
\end{equation}

$Z(s_1, s_2, \cdots, s_N)$ is the observed variables of $(s_1, s_2, \cdots, s_N)$, $ h_{s_0}(s_1, s_2, \cdots, s_N)$ is the distance between $(s_1, s_2, \cdots, s_N)$ and $s_0$. $N$ is the number of chosen neighbors.
