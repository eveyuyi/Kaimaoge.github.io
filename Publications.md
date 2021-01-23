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
          GNN for Kriging
          </div>
        </div>
      </td>
          <td><strong>Y. Wu</strong>, Zhuang, D, Labbe, A, & Sun, L.*</td>
      <td>
        Inductive Graph Neural Networks for Spatiotemporal Kriging<br>
                <p class="infolinks"> 
                  [<a href="javascript:toggleInfo('wu2020inductive','abstract')">Abstract</a>]
                  [<a href="javascript:toggleInfo('wu2020inductive','abstract')">BibTeX</a>] 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://arxiv.org/pdf/2006.07527">arXiv</a>]
                  [<a href="https://github.com/Kaimaoge/IGNNK">code</a>]
              </p>
        </td>
      <td>2021</td>
          <td>AAAI 2021</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <b>Abstract</b>: Time series forecasting and spatiotemporal kriging are the two most important tasks in spatiotemporal data analysis. Recent research on graph neural networks has made substantial progress in time series forecasting, while little attention has been paid to the kriging problem---recovering signals for unsampled locations/sensors. Most existing scalable kriging methods (e.g., matrix/tensor completion) are transductive, and thus full retraining is required when we have a new sensor to interpolate. In this paper, we develop an Inductive Graph Neural Network Kriging (IGNNK) model to recover data for unsampled sensors on a network/graph structure. To generalize the effect of distance and reachability, we generate random subgraphs as samples and  corresponding adjacency matrix for each sample. By reconstructing all signals on each sample subgraph, IGNNK can effectively learn the spatial message passing mechanism. Empirical results on several real-world spatiotemporal datasets demonstrate the effectiveness of our model. In addition, we also find that the learned model can be successfully transferred to the same type of kriging tasks on an unseen dataset. Our results show that: 1) GNN is an efficient and effective tool for spatial kriging; 2) inductive GNNs can be trained using dynamic adjacency matrices; 3) a trained model can be transferred to new graph structures and 4) IGNNK can be used to generate virtual sensors.</div></td>
        </tr>
        <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><b>BibTeX</b>:
                <pre>@article{wu2020inductive,
  title={Inductive graph neural networks for spatiotemporal kriging},
  author={Wu, Yuankai and Zhuang, Dingyi and Labbe, Aurelie and Sun, Lijun},
  journal={arXiv preprint arXiv:2006.07527},
  year={2020}
}</pre>
      </td>
    </tr>
	</tbody>
</table>
