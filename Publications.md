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
          <td><strong>Y. Wu</strong>, Zhuang, D, Labbe, A, & Sun, L.*</td>
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
          <td><strong>Y. Wu</strong>, H. Tan, L. Qin, B. Ran, Z. Jiang.</td>
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
	</tbody>
</table>






