---
layout: post
title: "EC-Net: an Edge-aware Point set Consolidation Network"
date: 2018-07-16 17:44:18
categories: arXiv_CV
tags: arXiv_CV Sparse Face Deep_Learning
author: Lequan Yu, Xianzhi Li, Chi-Wing Fu, Daniel Cohen-Or, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Point clouds obtained from 3D scans are typically sparse, irregular, and noisy, and required to be consolidated. In this paper, we present the first deep learning based edge-aware technique to facilitate the consolidation of point clouds. We design our network to process points grouped in local patches, and train it to learn and help consolidate points, deliberately for edges. To achieve this, we formulate a regression component to simultaneously recover 3D point coordinates and point-to-edge distances from upsampled features, and an edge-aware joint loss function to directly minimize distances from output points to 3D meshes and to edges. Compared with previous neural network based works, our consolidation is edge-aware. During the synthesis, our network can attend to the detected sharp edges and enable more accurate 3D reconstructions. Also, we trained our network on virtual scanned point clouds, demonstrated the performance of our method on both synthetic and real point clouds, presented various surface reconstruction results, and showed how our method outperforms the state-of-the-arts.

##### Abstract (translated by Google)
从3D扫描获得的点云通常是稀疏的，不规则的和嘈杂的，并且需要被合并。在本文中，我们提出了第一种基于深度学习的边缘感知技术，以促进点云的整合。我们设计我们的网络来处理分组在本地补丁中的点，并训练它以学习和帮助巩固点，故意为边缘。为了实现这一目标，我们制定了回归组件，以同时恢复上采样特征的3D点坐标和点到边距离，以及边缘感知关节损失函数，以直接最小化从输出点到3D网格和边缘的距离。与以前基于神经网络的工作相比，我们的整合是边缘感知的。在综合过程中，我们的网络可以处理检测到的锐边并实现更精确的3D重建。此外，我们在虚拟扫描点云上训练我们的网络，演示了我们的方法在合成和实际点云上的表现，呈现了各种表面重建结果，并展示了我们的方法如何优于现有技术。

##### URL
[http://arxiv.org/abs/1807.06010](http://arxiv.org/abs/1807.06010)

##### PDF
[http://arxiv.org/pdf/1807.06010](http://arxiv.org/pdf/1807.06010)

