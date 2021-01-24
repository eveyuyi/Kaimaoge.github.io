---
layout: page
permalink: /research/index.html
title: Published Researches
---

## Spatio-temporal data modeling 

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
         <tr id="zhang2020understanding" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/dr.PNG" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">Disentangled representation of urban mobility data</font><br /> </center>
          </div>
        </div>
      </td>
          <td><font size="2">H. Zhang, <strong>Y. Wu*</strong>,, H. Tan, H. Dong, F. Ding, B. Ran </font> </td>
      <td>
       Understanding and Modeling Urban Mobility Dynamics via Disentangled Representation Learning<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://ieeexplore.ieee.org/abstract/document/9239884?casa_token=GHlSjX7JudcAAAAA:F83HoixincVTNerTyVjcuhVY9su7hDQvUPS93xmzsrIghhRBeFeyUlPcs3RFdyMCjpy51I_lM4M">Paper</a>]
              </p>
        </td>
      <td>2020</td>
          <td>IEEE transactions on Intelligent Transportation Systems</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Understanding the underlying patterns of the urban mobility dynamics is essential for both the traffic state estimation and management of urban facilities and services. Due to the coupling relationship of generative factors in spatial-temporal domain, it is challenging to model the citywide traffic dynamics under a structural pattern of critical features such as hours of days, days of weeks and weather conditions. To address this challenge, this article develops a disentangled representation learning framework to learn an interpretable factorized representation of the independent data generative factors. In order to make full use of the knowledge on generative factors, this article proposes spatial-temporal generative adversarial network (ST-GAN) to assign the generative factors of traffic flow to the feature vector in latent space and reconstructs the high-dimensional citywide traffic flow from the given factors. With the help of the disentangled representations, the decomposed feature vector in latent space discloses the relationship between underlying patterns and citywide traffic dynamics. Several comprehensively experiments show that ST-GAN not only effectively improves the prediction accuracy but also promisingly characterize structural properties of the traffic evolution process. </p>
</details>
		  </div></td>
        </tr>
        <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@ARTICLE{9239884,
  author={H. {Zhang} and Y. {Wu} and H. {Tan} and H. {Dong} and F. {Ding} and B. {Ran}},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={Understanding and Modeling Urban Mobility Dynamics via Disentangled Representation Learning}, 
  year={2020},
  volume={},
  number={},
  pages={1-11},
  doi={10.1109/TITS.2020.3030259}
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
       Short-Term Traffic Prediction Based on Dynamic Tensor Completion<br>
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

## Data-driven ITS system control

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
    <tr id="wu2020differential" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/DVSL.jpg" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">Variable speed limits control as an MDP</font><br /> </center>
          </div>
        </div>
      </td>
          <td> <font size="2"><strong>Y. Wu</strong>, H. Tan, L. Qin, B. Ran* </font></td>
      <td>
        Differential variable speed limits control for freeway recurrent bottlenecks via deep actor-critic algorithm<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://www.sciencedirect.com/science/article/abs/pii/S0968090X20305647">Paper</a>]
                  [<a href="https://github.com/Kaimaoge/SUMO-DVSL">code</a>]
              </p>
        </td>
      <td>2020</td>
          <td>Transportation Research Part C</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Variable speed limit (VSL) control is a flexible way to improve traffic conditions, increase safety, and reduce emissions. There is an emerging trend of using reinforcement learning methods for VSL control. Currently, deep learning is enabling reinforcement learning to develop autonomous control agents for problems that were previously intractable. In this paper, a more effective deep reinforcement learning (DRL) model is developed for differential variable speed limit (DVSL) control, in which dynamic and distinct speed limits among lanes can be imposed. The proposed DRL model uses a novel actor-critic architecture to learn a large number of discrete speed limits in a continuous action space. Different reward signals, such as total travel time, bottleneck speed, emergency braking, and vehicular emissions are used to train the DVSL controller, and a comparison between these reward signals is conducted. The proposed DRL-based DVSL controllers are tested on a freeway with a simulated recurrent bottleneck. The simulation results show that the DRL based DVSL control strategy is able to improve the safety, efficiency and environment-friendliness of the freeway. In order to verify whether the controller generalizes to real world implementation, we also evaluate the generalization of the controllers on environments with different driving behavior attributes. and the robustness of the DRL agent is observed from the results. </p>
</details>
		  </div></td>
        </tr>
     <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@article{wu2020differential,
  title={Differential variable speed limits control for freeway recurrent bottlenecks via deep actor-critic algorithm},
  author={Wu, Yuankai and Tan, Huachun and Qin, Lingqiao and Ran, Bin},
  journal={Transportation research part C: emerging technologies},
  volume={117},
  pages={102649},
  year={2020},
  publisher={Elsevier}
}</pre></p>
</details>
      </td>
    </tr>
    <tr id="wu2019deep" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/Energy.jpg" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">HEV EMS as an MDP</font><br /> </center>
          </div>
        </div>
      </td>
          <td> <font size="2"><strong>Y. Wu</strong>, H. Tan, J. Peng, H. Zhang, H. He </font></td>
      <td>
        Deep reinforcement learning of energy management with continuous control strategy and traffic information for a series-parallel plug-in hybrid electric bus<br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://www.sciencedirect.com/science/article/pii/S030626191930652X?casa_token=AxGfRLIxX4QAAAAA:MARubarawwfJ3sM2sxJWcx14cmpzpSmp5B8Qv0Ngl2DRJInFGes_GOgns-J3R98ZwYjC0YM32hDB">Paper</a>]
              </p>
        </td>
      <td>2019</td>
          <td>Applied Energy</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Hybrid electric vehicles offer an immediate solution for emissions reduction and fuel displacement under the current technique level. Energy management strategies are critical for improving fuel economy of hybrid electric vehicles. In this paper we propose a energy management strategy for a series-parallel plug-in hybrid electric bus based on deep deterministic policy gradients. Specifically, deep deterministic policy gradients is an actor-critic, model-free reinforcement learning algorithm that can assign the optimal energy split of the bus over continuous spaces. We consider that the buses are driving in a fixed bus line, where driving cycle is constrained by the traffic. The traffic information and number of passengers are also incorporated into the energy management system. The deep reinforcement learning based energy management agent is trained with a large amount of driving cycles that generated from traffic simulation. Experiments on the traffic simulation driving cycles show that the proposed approach outperforms conventional reinforcement learning approach and exhibits performance close to the global optimal dynamic programming. Moreover, it also has great generality to the standard driving cycles that are significantly different with the ones that it has been trained with. We also show some interesting attributes of learned energy management strategies through visualizations of the actor and critic. The main contribution of this study is to explore the incorporation of traffic information within hybrid electric vehicle energy managment through advanced intelligent algorithms. </p>
</details>
		  </div></td>
        </tr>
     <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@article{wu2019deep,
  title={Deep reinforcement learning of energy management with continuous control strategy and traffic information for a series-parallel plug-in hybrid electric bus},
  author={Wu, Yuankai and Tan, Huachun and Peng, Jiankun and Zhang, Hailong and He, Hongwen},
  journal={Applied energy},
  volume={247},
  pages={454--466},
  year={2019},
  publisher={Elsevier}
}</pre></p>
</details>
      </td>
    </tr>
        <tr id="lian2020cross" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/transfer_learning.PNG" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">Transfer knowledge between EMSs of different HEVs</font><br /> </center>
          </div>
        </div>
      </td>
          <td> <font size="2">R. Lian, H. Tan, J. Peng, Q. Li, <strong>Y. Wu*</strong> </font></td>
      <td>
       Cross-Type Transfer for Deep Reinforcement Learning Based Hybrid Electric Vehicle Energy Management <br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://ieeexplore.ieee.org/abstract/document/9105110">Paper</a>]
		  [<a href="https://github.com/lryz0612/DRL-Energy-Management">Code1</a>]
		  [<a href="https://github.com/lryz0612/Transfer_DRL_EMS">Code2</a>]
              </p>
        </td>
      <td>2020</td>
          <td>IEEE Transactions on Vehicular Technology</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Developing energy management strategies (EMSs) for different types of hybrid electric vehicles (HEVs) is a time-consuming and laborious task for automotive engineers. Experienced engineers can reduce the developing cycle by exploiting the commonalities between different types of HEV EMSs. Aiming at improving the efficiency of HEV EMSs development automatically, this paper proposes a transfer learning based method to achieve the cross-type knowledge transfer between deep reinforcement learning (DRL) based EMSs. Specifically, knowledge transfer among four significantly different types of HEVs is studied. We first use massive driving cycles to train a DRL-based EMS for Prius. Then the parameters of its deep neural networks, wherein the common knowledge of energy management is captured, are transferred into EMSs of a power-split bus, a series vehicle and a series-parallel bus. Finally, the parameters of 3 different HEV EMSs are fine-tuned in a small dataset. Simulation results indicate that, by incorporating transfer learning (TL) into DRL-based EMS for HEVs, an average 70% gap from the baseline in respect of convergence efficiency has been achieved. Our study also shows that TL can transfer knowledge between two HEVs that have significantly different structures. Overall, TL is conducive to boost the development process for HEV EMS. </p>
</details>
		  </div></td>
        </tr>
     <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@article{lian2020cross,
  title={Cross-type transfer for deep reinforcement learning based hybrid electric vehicle energy management},
  author={Lian, Renzong and Tan, Huachun and Peng, Jiankun and Li, Qin and Wu, Yuankai},
  journal={IEEE Transactions on Vehicular Technology},
  volume={69},
  number={8},
  pages={8367--8380},
  year={2020},
  publisher={IEEE}
}</pre></p>
</details>
      </td>
    </tr>
            <tr id="wang2020hybrid" class="entry">
          <td>
        <div class="polaroid">
          <img src="https://kaimaoge.github.io/pub_img/CV_EMS.PNG" width="600" class="research_img">
          <div class="container">
          <center> <font size="1">HEV EMS combined with CV and DRL</font><br /> </center>
          </div>
        </div>
      </td>
          <td> <font size="2">Y. Wang, H. Tan, <strong>Y. Wu*</strong>, J. Peng  </font></td>
      <td>
       Hybrid electric vehicle energy management with computer vision and deep reinforcement learning <br>
                <p class="infolinks"> 
                  <!-- [<a href="https://arxiv.org/pdf/2006.07527.pdf">PDF</a>] -->
                  [<a href="https://ieeexplore.ieee.org/abstract/document/9165215?casa_token=ePPo5pWS7T8AAAAA:9DvyFYAyeNx9tYloHjbJz-B3buNQ6qE3D5dGE0zzdVWbDMxc66MmHkSx0ZAB2xAxeoqLRPSGT_E">Paper</a>]
              </p>
        </td>
      <td>2020</td>
          <td>IEEE Transactions on Industrial Informatics</td>
        </tr>
        <tr id="abs_wu2020inductive" class="abstract noshow">
          <td colspan="5"><div align="justify"> <details><summary><b>Abstract</b>:</summary> <p>
		  Modern automotive systems have equipped with a highly increasing number of computer vision hardware/softwares, which are considered to be beneficial for eco-driving. This work combines computer vision and deep reinforcement learning to improve the fuel economy of hybrid electric vehicles. The convolutional neural networks-based object detection method is utilized to extract available visual information from on-board cameras. The visual information is used as a state input for a continuous deep reinforcement learning model to output energy management strategies. In order to evaluate the proposed method, we construct 100 kilometers real city and highway driving cycles, in which visual information is incorporated. The results show that the deep reinforcement learning based system with visual information consumes 4.3% to 8.8% less fuel compared with the one without visual information, and achieves 96.5% fuel economy of the dynamic programming. </p>
</details>
		  </div></td>
        </tr>
     <tr id="bib_wu2020inductive" class="bibtex noshow">
          <td colspan="5"><details><summary><b>Bibtex</b>:</summary> <p>
                <pre>@ARTICLE{9165215,
  author={Y. {Wang} and H. {Tan} and Y. {Wu} and J. {Peng}},
  journal={IEEE Transactions on Industrial Informatics}, 
  title={Hybrid electric vehicle energy management with computer vision and deep reinforcement learning}, 
  year={2020},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TII.2020.3015748}
  }</pre></p>
</details>
      </td>
    </tr>
	</tbody>
</table>




