---
layout: post
title: "A Capsule Network for Traffic Speed Prediction in Complex Road Networks"
date: 2018-07-23 10:40:22
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge CNN Deep_Learning Prediction Relation
author: Youngjoo Kim, Peng Wang, Yifei Zhu, Lyudmila Mihaylova
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an approach for vehicular spatio-temporal characteristics prediction of traffic flow in complex road networks with a deep learning approach. Traffic flow data from inductive sensors are essentially a time series, which is also spatially related to traffic in different road segments. The spatio-temporal traffic data from can be converted into an image where the traffic data are expressed in a 3D space with respect to space and time axes. Although convolutional neural networks (CNNs) have been showing surprising performance in understanding images, they have a major drawback. In the max pooling operation CNNs are losing important information by locally taking the highest activation values. The inter-relationship in traffic data measured by sparsely located sensors in different time intervals should not be neglected in order to obtain accurate predictions. Thus, we propose a neural network with capsules that replaces max pooling by dynamic routing. This is the first approach that employs the capsule network on a time series forecasting problem, to our best knowledge. Moreover, an experiment on real traffic speed data measured in the Santander city of Spain demonstrates the proposed method outperforms the state-of-the-art method based on a CNN by 8.6% in root mean squared error.

##### Abstract (translated by Google)
本文提出了一种基于深度学习方法的复杂路网交通流车辆时空特征预测方法。来自感应传感器的交通流数据基本上是时间序列，其在空间上也与不同路段中的交通相关。来自时空的交通数据可以被转换成图像，其中交通数据相对于空间和时间轴在3D空间中表达。尽管卷积神经网络（CNN）在理解图像方面已经表现出令人惊讶的性能，但它们具有一个主要缺点。在最大池操作中，CNN通过本地获取最高激活值而丢失重要信息。为了获得准确的预测，不应忽略在不同时间间隔内由稀疏定位的传感器测量的交通数据中的相互关系。因此，我们提出了一个带有胶囊的神经网络，通过动态路由替换最大池。根据我们的最佳知识，这是第一种在时间序列预测问题上采用胶囊网络的方法。此外，在西班牙桑坦德市测量的实际交通速度数据的实验表明，所提出的方法优于基于CNN的最新方法，均方根误差为8.6％。

##### URL
[http://arxiv.org/abs/1807.10603](http://arxiv.org/abs/1807.10603)

##### PDF
[http://arxiv.org/pdf/1807.10603](http://arxiv.org/pdf/1807.10603)

