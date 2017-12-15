---
layout: post
title: "Efficient Training of Very Deep Neural Networks for Supervised Hashing"
date: 2016-04-21 21:49:21
categories: arXiv_CV
tags: arXiv_CV
author: Ziming Zhang, Yuting Chen, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose training very deep neural networks (DNNs) for supervised learning of hash codes. Existing methods in this context train relatively "shallow" networks limited by the issues arising in back propagation (e.e. vanishing gradients) as well as computational efficiency. We propose a novel and efficient training algorithm inspired by alternating direction method of multipliers (ADMM) that overcomes some of these limitations. Our method decomposes the training process into independent layer-wise local updates through auxiliary variables. Empirically we observe that our training algorithm always converges and its computational complexity is linearly proportional to the number of edges in the networks. Empirically we manage to train DNNs with 64 hidden layers and 1024 nodes per layer for supervised hashing in about 3 hours using a single GPU. Our proposed very deep supervised hashing (VDSH) method significantly outperforms the state-of-the-art on several benchmark datasets.

##### Abstract (translated by Google)
在本文中，我们提出了训练非常深的神经网络（DNNs）监督学习散列码。现有的方法在这种情况下训练由于反向传播（即消失梯度）所引起的问题以及计算效率而受到限制的相对“浅”网络。我们提出了一种新颖而有效的训练算法，这种算法受交替方向乘法器（ADMM）的启发，克服了这些局限性。我们的方法通过辅助变量将训练过程分解成独立的分层局部更新。经验上我们观察到，我们的训练算法总是收敛，其计算复杂度与网络中边缘的数量成线性比例关系。实际上，我们使用单个GPU在大约3个小时的时间内，对每层64个隐藏层和1024个节点进行DNN进行监督散列训练。我们提出的非常深入的监督散列（VDSH）方法明显优于几个基准数据集的最新技术。

##### URL
[https://arxiv.org/abs/1511.04524](https://arxiv.org/abs/1511.04524)

##### PDF
[https://arxiv.org/pdf/1511.04524](https://arxiv.org/pdf/1511.04524)

