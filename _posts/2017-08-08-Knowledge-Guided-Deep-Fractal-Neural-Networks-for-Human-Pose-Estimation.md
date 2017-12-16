---
layout: post
title: "Knowledge-Guided Deep Fractal Neural Networks for Human Pose Estimation"
date: 2017-08-08 21:05:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation
author: Guanghan Ning, Zhi Zhang, Zhihai He
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose estimation using deep neural networks aims to map input images with large variations into multiple body keypoints which must satisfy a set of geometric constraints and inter-dependency imposed by the human body model. This is a very challenging nonlinear manifold learning process in a very high dimensional feature space. We believe that the deep neural network, which is inherently an algebraic computation system, is not the most effecient way to capture highly sophisticated human knowledge, for example those highly coupled geometric characteristics and interdependence between keypoints in human poses. In this work, we propose to explore how external knowledge can be effectively represented and injected into the deep neural networks to guide its training process using learned projections that impose proper prior. Specifically, we use the stacked hourglass design and inception-resnet module to construct a fractal network to regress human pose images into heatmaps with no explicit graphical modeling. We encode external knowledge with visual features which are able to characterize the constraints of human body models and evaluate the fitness of intermediate network output. We then inject these external features into the neural network using a projection matrix learned using an auxiliary cost function. The effectiveness of the proposed inception-resnet module and the benefit in guided learning with knowledge projection is evaluated on two widely used benchmarks. Our approach achieves state-of-the-art performance on both datasets.

##### Abstract (translated by Google)
使用深度神经网络的人体姿态估计旨在将具有大变化的输入图像映射到多个身体关键点，这些身体关键点必须满足由人体模型施加的一组几何约束和相互依赖性。在非常高维的特征空间中，这是一个非常具有挑战性的非线性流形学习过程。我们认为深层神经网络本身就是一个代数计算系统，并不是捕捉高度复杂的人类知识的最有效方式，例如高度耦合的几何特征和人类关键点之间的相互依赖性。在这项工作中，我们建议探索如何外部知识可以有效地代表和注入深层神经网络，以指导其训练过程中使用学习预测强加适当的先验。具体而言，我们使用堆叠式沙漏设计和初始模块来构建分形网络，将人体姿态图像回归到热图中，而没有明确的图形建模。我们利用视觉特征对外部知识进行编码，这些特征能够表征人体模型的约束条件，并评估中间网络输出的适应度。然后，我们使用辅助成本函数学习的投影矩阵将这些外部特征注入到神经网络中。在两个广泛使用的基准上评估所提出的初始资源模块的有效性和知识预测的导向学习的益处。我们的方法在两个数据集上都达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1705.02407](https://arxiv.org/abs/1705.02407)

##### PDF
[https://arxiv.org/pdf/1705.02407](https://arxiv.org/pdf/1705.02407)

