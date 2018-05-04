---
layout: post
title: "Mapping Road Lanes Using Laser Remission and Deep Neural Networks"
date: 2018-04-27 19:45:54
categories: arXiv_RO
tags: arXiv_RO Segmentation
author: Raphael V. Carneiro, Rafael C. Nascimento, Rânik Guidolini, Vinicius B. Cardoso, Thiago Oliveira-Santos, Claudine Badue, Alberto F. De Souza
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the use of deep neural networks (DNN) for solving the problem of inferring the position and relevant properties of lanes of urban roads with poor or absent horizontal signalization, in order to allow the operation of autonomous cars in such situations. We take a segmentation approach to the problem and use the Efficient Neural Network (ENet) DNN for segmenting LiDAR remission grid maps into road maps. We represent road maps using what we called road grid maps. Road grid maps are square matrixes and each element of these matrixes represents a small square region of real-world space. The value of each element is a code associated with the semantics of the road map. Our road grid maps contain all information about the roads' lanes required for building the Road Definition Data Files (RDDFs) that are necessary for the operation of our autonomous car, IARA (Intelligent Autonomous Robotic Automobile). We have built a dataset of tens of kilometers of manually marked road lanes and used part of it to train ENet to segment road grid maps from remission grid maps. After being trained, ENet achieved an average segmentation accuracy of 83.7%. We have tested the use of inferred road grid maps in the real world using IARA on a stretch of 3.7 km of urban roads and it has shown performance equivalent to that of the previous IARA's subsystem that uses a manually generated RDDF.

##### Abstract (translated by Google)
我们提出使用深度神经网络（DNN）来解决推断具有较差或缺少水平信号的城市道路的位置和相关属性的问题，以便允许在这种情况下操作自动驾驶汽车。我们采用分割方法解决问题，并使用高效神经网络（ENet）DNN将LiDAR缓解网格地图分割成路线图。我们使用我们所谓的道路网格地图来表示道路地图。道路网格图是方矩阵，这些矩阵的每个元素代表真实世界空间的一个小方形区域。每个元素的值是与路线图的语义相关的代码。我们的道路网格图包含了构建道路定义数据文件（RDDF）所需的道路车道的所有信息，这些道路定义数据文件（RDDF）对于我们的自动驾驶汽车IARA（智能自动机器人汽车）的运行是必需的。我们已经建立了数十公里的手动标记道路车道数据集，并使用它的一部分来训练ENet，从缓解网格图中分割道路网格图。经过训练后，ENet实现了83.7％的平均分割精度。我们使用IARA在3.7公里长的城市道路上测试了现实世界中推断出的道路网格地图的使用情况，并表现出与先前IARA使用手动生成的RDDF的子系统相当的性能。

##### URL
[https://arxiv.org/abs/1804.10662](https://arxiv.org/abs/1804.10662)

##### PDF
[https://arxiv.org/pdf/1804.10662](https://arxiv.org/pdf/1804.10662)

