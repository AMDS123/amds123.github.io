---
layout: post
title: "Generative Model with Coordinate Metric Learning for Object Recognition Based on 3D Models"
date: 2017-05-24 03:22:18
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference Classification Recognition
author: Yida Wang, Weihong Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Given large amount of real photos for training, Convolutional neural network shows excellent performance on object recognition tasks. However, the process of collecting data is so tedious and the background are also limited which makes it hard to establish a perfect database. In this paper, our generative model trained with synthetic images rendered from 3D models reduces the workload of data collection and limitation of conditions. Our structure is composed of two sub-networks: semantic foreground object reconstruction network based on Bayesian inference and classification network based on multi-triplet cost function for avoiding over-fitting problem on monotone surface and fully utilizing pose information by establishing sphere-like distribution of descriptors in each category which is helpful for recognition on regular photos according to poses, lighting condition, background and category information of rendered images. Firstly, our conjugate structure called generative model with metric learning utilizing additional foreground object channels generated from Bayesian rendering as the joint of two sub-networks. Multi-triplet cost function based on poses for object recognition are used for metric learning which makes it possible training a category classifier purely based on synthetic data. Secondly, we design a coordinate training strategy with the help of adaptive noises acting as corruption on input images to help both sub-networks benefit from each other and avoid inharmonious parameter tuning due to different convergence speed of two sub-networks. Our structure achieves the state of the art accuracy of over 50\% on ShapeNet database with data migration obstacle from synthetic images to real photos. This pipeline makes it applicable to do recognition on real images only based on 3D models.

##### Abstract (translated by Google)
鉴于大量的实际照片用于训练，卷积神经网络在物体识别任务上表现出优异的性能。但是数据采集过程繁琐，背景也比较有限，难以建立完善的数据库。在本文中，我们使用3D模型渲染合成图像的生成模型减少了数据收集和条件限制的工作量。我们的结构由两个子网组成：基于贝叶斯推理的语义前景对象重构网络和基于多重三元代价函数的分类网络，避免单调表面上的过拟合问题，通过建立类球面分布来充分利用姿态信息根据渲染图像的姿态，照明条件，背景和类别信息，对每个类别中的描述符进行识别，有助于识别常规照片。首先，我们的共轭结构称为具有度量学习的生成模型，利用由贝叶斯渲染产生的附加前景目标通道作为两个子网络的联合。基于姿态对象识别的多三元代价函数被用于度量学习，这使得可以纯粹基于合成数据来训练类别分类器。其次，利用自适应噪声作为输入图像中的腐败现象，设计了一种协调训练策略，有助于两个子网络相互获益，避免了两个子网络收敛速度不同造成的参数不协调问题。我们的结构在ShapeNet数据库上实现了超过50％的最高精度，并具有从合成图像到真实照片的数据迁移障碍。该流水线使其仅适用于基于3D模型对真实图像进行识别。

##### URL
[https://arxiv.org/abs/1705.08590](https://arxiv.org/abs/1705.08590)

##### PDF
[https://arxiv.org/pdf/1705.08590](https://arxiv.org/pdf/1705.08590)

