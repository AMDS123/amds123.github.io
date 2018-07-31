---
layout: post
title: "Bike Flow Prediction with Multi-Graph Convolutional Networks"
date: 2018-07-28 13:35:37
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning Prediction Relation
author: Di Chai, Leye Wang, Qiang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
One fundamental issue in managing bike sharing systems is the bike flow prediction. Due to the hardness of predicting the flow for a single station, recent research works often predict the bike flow at cluster-level. While such studies gain satisfactory prediction accuracy, they cannot directly guide some fine-grained bike sharing system management issues at station-level. In this paper, we revisit the problem of the station-level bike flow prediction, aiming to boost the prediction accuracy leveraging the breakthroughs of deep learning techniques. We propose a new multi-graph convolutional neural network model to predict the bike flow at station-level, where the key novelty is viewing the bike sharing system from the graph perspective. More specifically, we construct multiple inter-station graphs for a bike sharing system. In each graph, nodes are stations, and edges are a certain type of relations between stations. Then, multiple graphs are constructed to reflect heterogeneous relationships (e.g., distance, ride record correlation). Afterward, we fuse the multiple graphs and then apply the convolutional layers on the fused graph to predict station-level future bike flow. In addition to the estimated bike flow value, our model also gives the prediction confidence interval so as to help the bike sharing system managers make decisions. Using New York City and Chicago bike sharing data for experiments, our model can outperform state-of-the-art station-level prediction models by reducing 25.1% and 17.0% of prediction error in New York City and Chicago, respectively.

##### Abstract (translated by Google)
管理自行车共享系统的一个基本问题是自行车流量预测。由于预测单站的流量的硬度，最近的研究工作通常预测集群级别的自行车流量。虽然这些研究获得了令人满意的预测准确性，但它们无法在站级直接指导一些细粒度的自行车共享系统管理问题。在本文中，我们重新审视了站级自行车流量预测的问题，旨在利用深度学习技术的突破提高预测精度。我们提出了一种新的多图卷积神经网络模型来预测车站级别的自行车流量，其中关键的新颖性是从图形角度观察自行车共享系统。更具体地说，我们为自行车共享系统构建了多个站间图。在每个图中，节点是站，并且边是站之间的某种类型的关系。然后，构造多个图以反映异构关系（例如，距离，乘坐记录相关性）。之后，我们融合多个图形，然后在融合图上应用卷积层来预测站级未来自行车流量。除了估计的自行车流量值之外，我们的模型还给出了预测置信区间，以帮助自行车共享系统管理员做出决策。利用纽约市和芝加哥自行车共享数据进行实验，我们的模型可以通过分别减少纽约市和芝加哥的预测误差的25.1％和17.0％来超越最先进的站级预测模型。

##### URL
[http://arxiv.org/abs/1807.10934](http://arxiv.org/abs/1807.10934)

##### PDF
[http://arxiv.org/pdf/1807.10934](http://arxiv.org/pdf/1807.10934)

