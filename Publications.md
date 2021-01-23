---
layout: page
permalink: /pub/index.html
title: Selected Publications
---

<table style="width:100%">
    <thead>
		<tr>
			<th width="25%">Highlight</th>
			<th width="21%">Authors</th>
			<th width="32%">Title</th>
			<th width="2%">Year</th>
			<th width="20%">Journal/Proceedings</th>
		</tr>
    </thead>
	<tbody>
    <tr id="wu2020inductive" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/ignnk.PNG" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">GNN for Kriging</font><br /> </center>
          </div>
        </div>
      </td>
          <td> <font size="2"> <strong>Y. Wu</strong>, Zhuang, D, Labbe, A, & Sun, L.* </font></td>
      <td>
        Inductive Graph Neural Networks for Spatiotemporal Kriging<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://arxiv.org/pdf/2006.07527">arXiv</a>]
                  [<a href="https://github.com/Kaimaoge/IGNNK">code</a>]
              </p>
        </td>
      <td>2021</td>
          <td>AAAI 2021</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Time series forecasting and spatiotemporal kriging are the two most important tasks in spatiotemporal data analysis. Recent research on graph neural networks has made substantial progress in time series forecasting, while little attention has been paid to the kriging problem---recovering signals for unsampled locations/sensors. Most existing scalable kriging methods (e.g., matrix/tensor completion) are transductive, and thus full retraining is required when we have a new sensor to interpolate. In this paper, we develop an Inductive Graph Neural Network Kriging (IGNNK) model to recover data for unsampled sensors on a network/graph structure. To generalize the effect of distance and reachability, we generate random subgraphs as samples and  corresponding adjacency matrix for each sample. By reconstructing all signals on each sample subgraph, IGNNK can effectively learn the spatial message passing mechanism. Empirical results on several real-world spatiotemporal datasets demonstrate the effectiveness of our model. In addition, we also find that the learned model can be successfully transferred to the same type of kriging tasks on an unseen dataset. Our results show that: 1) GNN is an efficient and effective tool for spatial kriging; 2) inductive GNNs can be trained using dynamic adjacency matrices; 3) a trained model can be transferred to new graph structures and 4) IGNNK can be used to generate virtual sensors. </p>
</details>
		  </div></td>
        </tr>
        <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@article{wu2020inductive,
  title={Inductive graph neural networks for spatiotemporal kriging},
  author={Wu, Yuankai and Zhuang, Dingyi and Labbe, Aurelie and Sun, Lijun},
  journal={arXiv preprint arXiv:2006.07527},
  year={2020}
}</pre></p>
</details>
      </td>
    </tr>
      <tr id="wu2018hybrid" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/TRC.jpg" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">Hybrid CNN-RNN traffic forecastor</font><br /> </center>
          </div>
        </div>
      </td>
          <td><font size="2"> <strong>Y. Wu</strong>, H. Tan, L. Qin, B. Ran, Z. Jiang. </font> </td>
      <td>
        A hybrid deep learning based traffic flow prediction method and its understanding<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://www.sciencedirect.com/science/article/pii/S0968090X18302651?casa_token=S9i_2E-eysgAAAAA:BB1qR2bgJBl0mYnZARG9XNUi41yknWZDmAkvvmVLKO2gpMQd0ZAAUt0IWpEthpIcopXO0UvUHifr">Paper</a>]
              </p>
        </td>
      <td>2018</td>
          <td>Transportation Research Part C</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Deep neural networks (DNNs) have recently demonstrated the capability to predict traffic flow with big data. While existing DNN models can provide better performance than shallow models, it is still an open issue of making full use of spatial-temporal characteristics of the traffic flow to improve their performance. In addition, our understanding of them on traffic data remains limited. This paper proposes a DNN based traffic flow prediction model (DNN-BTF) to improve the prediction accuracy. The DNN-BTF model makes full use of weekly/daily periodicity and spatial-temporal characteristics of traffic flow. Inspired by recent work in machine learning, an attention based model was introduced that automatically learns to determine the importance of past traffic flow. The convolutional neural network was also used to mine the spatial features and the recurrent neural network to mine the temporal features of traffic flow. We also showed through visualization how DNN-BTF model understands traffic flow data and presents a challenge to conventional thinking about neural networks in the transportation field that neural networks is purely a “black-box” model. Data from open-access database PeMS was used to validate the proposed DNN-BTF model on a long-term horizon prediction task. Experimental results demonstrated that our method outperforms the state-of-the-art approaches. </p>
</details>
		  </div></td>
        </tr>
        <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@article{wu2018hybrid,
  title={A hybrid deep learning based traffic flow prediction method and its understanding},
  author={Wu, Yuankai and Tan, Huachun and Qin, Lingqiao and Ran, Bin and Jiang, Zhuxi},
  journal={Transportation Research Part C: Emerging Technologies},
  volume={90},
  pages={166--180},
  year={2018},
  publisher={Elsevier}
}</pre></p>
</details>
      </td>
    </tr>
    <tr id="wu2018fused" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/TNNLS.PNG" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">Multi-mode features obtained from FCP</font><br /> </center>
          </div>
        </div>
      </td>
          <td><font size="2"> <strong>Y. Wu</strong>, H. Tan, Y. Li, J. Zhang, X. Chen </font> </td>
      <td>
       A Fused CP Factorization Method for Incomplete Tensors<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://ieeexplore.ieee.org/abstract/document/8421043">Paper</a>]
		  [<a href="https://github.com/Kaimaoge/Tensor-decomposition-completion-and-recovery-papers-and-codes/tree/master/NonnegativeFCP">Code</a>]
              </p>
        </td>
      <td>2018</td>
          <td>IEEE transactions on neural networks and learning systems</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Low-rank tensor completion methods have been advanced recently for modeling sparsely observed data with a multimode structure. However, low-rank priors may fail to interpret the model factors of general tensor objects. The most common method to address this drawback is to use regularizations together with the low-rank priors. However, due to the complex nature and diverse characteristics of real-world multiway data, the use of a single or a few regularizations remains far from efficient, and there are limited systematic experimental reports on the advantages of these regularizations for tensor completion. To fill these gaps, we propose a modified CP tensor factorization framework that fuses the l 2 norm constraint, sparseness (l 1 norm), manifold, and smooth information simultaneously. The factorization problem is addressed through a combination of Nesterov's optimal gradient descent method and block coordinate descent. Here, we construct a smooth approximation to the l 1 norm and TV norm regularizations, and then, the tensor factor is updated using the projected gradient method, where the step size is determined by the Lipschitz constant. Extensive experiments on simulation data, visual data completion, intelligent transportation systems, and GPS data of user involvement are conducted, and the efficiency of our method is confirmed by the results. Moreover, the obtained results reveal the characteristics of these commonly used regularizations for tensor completion in a certain sense and give experimental guidance concerning how to use them. </p>
</details>
		  </div></td>
        </tr>
        <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@ARTICLE{8421043,
  author={Y. {Wu} and H. {Tan} and Y. {Li} and J. {Zhang} and X. {Chen}},
  journal={IEEE Transactions on Neural Networks and Learning Systems}, 
  title={A Fused CP Factorization Method for Incomplete Tensors}, 
  year={2019},
  volume={30},
  number={3},
  pages={751-764},
  doi={10.1109/TNNLS.2018.2851612}
  }</pre></p>
</details>
      </td>
    </tr>
     <tr id="tan2016short" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/DTC.PNG" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">Dynamic tensor for forecasting</font><br /> </center>
          </div>
        </div>
      </td>
          <td><font size="2">H. Tan, <strong>Y. Wu</strong>, B. Shen, P.J. Jin, B. Ran. </font> </td>
      <td>
       A Fused CP Factorization Method for Incomplete Tensors<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://ieeexplore.ieee.org/abstract/document/7407622">Paper</a>]
              </p>
        </td>
      <td>2016</td>
          <td>IEEE transactions on Intelligent Transportation Systems</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Short-term traffic prediction plays a critical role in many important applications of intelligent transportation systems such as traffic congestion control and smart routing, and numerous methods have been proposed to address this issue in the literature. However, most, if not all, of them suffer from the inability to fully use the rich information in traffic data. In this paper, we present a novel short-term traffic flow prediction approach based on dynamic tensor completion (DTC), in which the traffic data are represented as a dynamic tensor pattern, which is able capture more information of traffic flow than traditional methods, namely, temporal variabilities, spatial characteristics, and multimode periodicity. A DTC algorithm is designed to use the multimode information to forecast traffic flow with a low-rank constraint. The proposed method is evaluated on real-world data sets and compared with other state-of-the-art methods, and the efficacy of the proposed approach is validated on the experiments of traffic flow prediction, particularly when dealing with incomplete traffic data. </p>
</details>
		  </div></td>
        </tr>
        <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@ARTICLE{7407622,
  author={H. {Tan} and Y. {Wu} and B. {Shen} and P. J. {Jin} and B. {Ran}},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={Short-Term Traffic Prediction Based on Dynamic Tensor Completion}, 
  year={2016},
  volume={17},
  number={8},
  pages={2123-2133},
  doi={10.1109/TITS.2015.2513411}
  }</pre></p>
</details>
      </td>
    </tr>
	</tbody>
</table>






