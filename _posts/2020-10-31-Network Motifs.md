
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

# Definition

A connected graph that has many occurrences in a network is called a motif of the network. 

Example: triangle motif. In other words, motif is a connection pattern in a graph.

<center>
    <img style="border-radius: 0.2025em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 6px 0 rgba(34,36,38,.08);" 
    src="https://raw.githubusercontent.com/Kaimaoge/Kaimaoge.github.io/master/images/triangle.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Figure １：A triangle motif in a graph</div>
</center>

# Discovery

Network motifs are characteristic sub-networks that appear more frequently than expected considering the degree distribution of a biological network. Motifs are of direct biological relevance. Network motif classification has shown that specific types of motifs perform specific biological functions. Originally identified in transcriptional regulatory networks in model organisms, motifs are now understood to be basic building blocks of biological networks. So the motifs are discovered from biological structures.

# Applications

Network motifs can be used for graph partition [1].


<center>
    <img style="border-radius: 0.2525em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 6px 0 rgba(34,36,38,.08);" 
    src="https://raw.githubusercontent.com/Kaimaoge/Kaimaoge.github.io/master/images/network_motif.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Figure 2：Reconstruct the graph via triangle motif</div>
</center>

[1] Li, Pei-Zhen, et al. "EdMot: An edge enhancement approach for motif-aware community detection." Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 2019.

