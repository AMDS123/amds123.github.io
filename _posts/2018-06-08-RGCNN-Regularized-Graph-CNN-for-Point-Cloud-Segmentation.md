---
layout: post
title: "RGCNN: Regularized Graph CNN for Point Cloud Segmentation"
date: 2018-06-08 02:50:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Classification Deep_Learning
author: Gusi Te, Wei Hu, Zongming Guo, Amin Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Point cloud, an efficient 3D object representation, has become popular with the development of depth sensing and 3D laser scanning techniques. It has attracted attention in various applications such as 3D tele-presence, navigation for unmanned vehicles and heritage reconstruction. The understanding of point clouds, such as point cloud segmentation, is crucial in exploiting the informative value of point clouds for such applications. Due to the irregularity of the data format, previous deep learning works often convert point clouds to regular 3D voxel grids or collections of images before feeding them into neural networks, which leads to voluminous data and quantization artifacts. In this paper, we instead propose a regularized graph convolutional neural network (RGCNN) that directly consumes point clouds. Leveraging on spectral graph theory, we treat features of points in a point cloud as signals on graph, and define the convolution over graph by Chebyshev polynomial approximation. In particular, we update the graph Laplacian matrix that describes the connectivity of features in each layer according to the corresponding learned features, which adaptively captures the structure of dynamic graphs. Further, we deploy a graph-signal smoothness prior in the loss function, thus regularizing the learning process. Experimental results on the ShapeNet part dataset show that the proposed approach significantly reduces the computational complexity while achieving competitive performance with the state of the art. Also, experiments show RGCNN is much more robust to both noise and point cloud density in comparison with other methods. We further apply RGCNN to point cloud classification and achieve competitive results on ModelNet40 dataset.

##### Abstract (translated by Google)
随着深度感应和三维激光扫描技术的发展，点云，一种高效的三维物体表示已成为流行。它在各种应用中引起了关注，如3D电视显示，无人驾驶车辆导航和遗产重建。点云的理解，如点云分割，对于利用点云的信息价值来处理这些应用至关重要。由于数据格式的不规则性，先前的深度学习工作常常将点云转换为规则的三维体素网格或图像集合，然后将它们馈送到神经网络中，这导致大量的数据和量化伪像。在本文中，我们提出了直接消耗点云的正则化图卷积神经网络（RGCNN）。利用谱图理论，我们将点云中的点的特征作为图上的信号处理，并通过切比雪夫多项式近似定义图上的卷积。特别是，我们根据相应的学习特征更新了图拉普拉斯矩阵，该矩阵描述了每个层中特征的连通性，这些特征自适应地捕获了动态图的结构。此外，我们在损失函数之前部署图形信号平滑度，从而规范学习过程。 ShapeNet零件数据集的实验结果表明，所提出的方法显着降低了计算复杂度，同时实现了与现有技术的竞争性表现。此外，实验表明，与其他方法相比，RGCNN对噪声和点云密度都更加稳健。我们进一步将RGCNN应用于点云分类，并在ModelNet40数据集上获得有竞争力的结果。

##### URL
[http://arxiv.org/abs/1806.02952](http://arxiv.org/abs/1806.02952)

##### PDF
[http://arxiv.org/pdf/1806.02952](http://arxiv.org/pdf/1806.02952)

