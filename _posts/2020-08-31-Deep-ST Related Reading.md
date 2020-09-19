# Deep ST Models

This is [my](https://Kaimaoge.github.io/) paper reading list about deep learning for spatiotemporal datasets. I will have preference on graph neural networks and temporal point process.I will update it once I find something intersting.

## CONTENT

- [General review on graph neural networks](##General-review-gnn)
- [Interesting Graph Neural Networks Structure](##Gnn-structure)
- [Graph Neural Networks for ST prediction](##Gnn-st-prediction)
- [Inductive Graph Neural Networks](##Inductive-gnn)
- [Deep Time Series Forecasting](##Deep-time-series)
- [Temporal Point Process](##Tpp)

## General-review-gnn

I am learning a recent book written by William L. Hamilton 

- [Graph Representation Learning Book](https://www.cs.mcgill.ca/~wlh/grl_book/)

Two survey papers that I always referred to 

- [Wu, Z., Pan, S., Chen, F., Long, G., Zhang, C., & Philip, S. Y. (2020). A comprehensive survey on graph neural networks. IEEE Transactions on Neural Networks and Learning Systems.](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9046288&casa_token=VAeauroZgfoAAAAA:sR2hwdE8mD-Va_sWmPLWE2S-5zXSVVUHEnmNsXE6Mqblcs2t8ZDAlj6-jXHx4bpKPErrXN-D&tag=1)

- [Zhou, J., Cui, G., Zhang, Z., Yang, C., Liu, Z., Wang, L., ... & Sun, M. (2018). Graph neural networks: A review of methods and applications. arXiv preprint arXiv:1812.08434.](https://arxiv.org/pdf/1812.08434.pdf?source=post_page---------------------------)

## Gnn-structure

- [Gao, Hongyang, and Shuiwang Ji. "Graph u-nets." arXiv preprint arXiv:1905.05178 (2019).](https://arxiv.org/pdf/1905.05178.pdf)

## Gnn-st-prediction

Those works are mainly concentrated on traffic forecasting. Traffic forecasting is a typical graph signal forecasting problem, so graph neural networks are suitable for capturing the spatial dependencies of traffic data.

- [Guo, S., Lin, Y., Feng, N., Song, C., & Wan, H. (2019, July). Attention based spatial-temporal graph convolutional networks for traffic flow forecasting. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 33, pp. 922-929).](https://www.aaai.org/ojs/index.php/AAAI/article/view/3881)

- [Wu, Z., Pan, S., Long, G., Jiang, J., & Zhang, C. (2019). Graph wavenet for deep spatial-temporal graph modeling. arXiv preprint arXiv:1906.00121.](https://arxiv.org/pdf/1906.00121.pdf)

- [Yu, B., Yin, H., & Zhu, Z. (2018, July). Spatio-temporal graph convolutional networks: a deep learning framework for traffic forecasting. In Proceedings of the 27th International Joint Conference on Artificial Intelligence (pp. 3634-3640).](https://dl.acm.org/doi/abs/10.5555/3304222.3304273)

- [Li, Y., Yu, R., Shahabi, C., & Liu, Y. (2018, February). Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting. In International Conference on Learning Representations.](https://openreview.net/forum?id=SJiHXGWAZ&noteId=SJiHXGWAZ)

## Inductive-gnn

Inductive learning setting can make the learned model adaptive to new/unseen sensors

- [Zhang, Muhan, and Yixin Chen. "Inductive Matrix Completion Based on Graph Neural Networks." International Conference on Learning Representations. 2019.](https://openreview.net/forum?id=ByxxgCEYDS)

- [Zeng, Hanqing, et al. "GraphSAINT: Graph Sampling Based Inductive Learning Method." International Conference on Learning Representations. 2019.](https://openreview.net/forum?id=BJe8pkHFwS)

- [Hamilton, W., Ying, Z., & Leskovec, J. (2017). Inductive representation learning on large graphs. In Advances in neural information processing systems (pp. 1024-1034).](https://papers.nips.cc/paper/6703-inductive-representation-learning-on-large-graphs.pdf)

## Deep-time-series

- [Salinas, D., Flunkert, V., Gasthaus, J., & Januschowski, T. (2020). DeepAR: Probabilistic forecasting with autoregressive recurrent networks. International Journal of Forecasting, 36(3), 1181-1191.](https://www.sciencedirect.com/science/article/pii/S0169207019301888)

- [Rangapuram, S. S., Seeger, M. W., Gasthaus, J., Stella, L., Wang, Y., & Januschowski, T. (2018). Deep state space models for time series forecasting. In Advances in neural information processing systems (pp. 7785-7794).](http://papers.nips.cc/paper/8004-deep-state-space-models-for-time-series-forecasting.pdf)

## Tpp

According to theoretical physicist, [reality is just a complex network of events onto which we project sequences of past, present and future](https://www.nature.com/articles/d41586-018-04558-7). Time series is fundamentally an aggregation of stochstically generated events. Temporal point process is a good way to model the event sequence.

- [Shchur, O., Biloš, M., & Günnemann, S. (2019, September). Intensity-Free Learning of Temporal Point Processes. In International Conference on Learning Representations.](https://openreview.net/forum?id=HygOjhEYDH&noteId=lg3jmZS8JLL)

- [Mei, H., & Eisner, J. M. (2017). The neural hawkes process: A neurally self-modulating multivariate point process. In Advances in Neural Information Processing Systems (pp. 6754-6764).](http://papers.nips.cc/paper/7252-the-neural-hawkes-process-a-neurally-self-modulating-multivariate-point-process.pdf)

- [Du, N., Dai, H., Trivedi, R., Upadhyay, U., Gomez-Rodriguez, M., & Song, L. (2016, August). Recurrent marked temporal point processes: Embedding event history to vector. In Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (pp. 1555-1564).](https://dl.acm.org/doi/pdf/10.1145/2939672.2939875?casa_token=vbgtERg8kiwAAAAA:dRyoO1HWQcuuL5XxGX1qRfYUFGma_FTi_ueT6nJzvYUi2WkghcMq_C9Px2kt4cDl3ldLvXhEdBcy)

A great tutorial from Max Planck Ins0tute for Intelligent Systems

- [Learning with Temporal Point Process](http://learning.mpi-sws.org/tpp-icml18/)

