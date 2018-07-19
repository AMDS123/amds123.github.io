---
layout: post
title: "Deep neural network based speech separation optimizing an objective estimator of intelligibility for low latency applications"
date: 2018-07-18 12:55:59
categories: arXiv_SD
tags: arXiv_SD RNN Memory_Networks
author: Gaurav Naithani, Joonas Nikunen, Lars Bramsløw, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
Mean square error (MSE) has been the preferred choice as loss function in the current deep neural network (DNN) based speech separation techniques. In this paper, we propose a new cost function with the aim of optimizing the extended short time objective intelligibility (ESTOI) measure. We focus on applications where low algorithmic latency ($\leq 10$ ms) is important. We use long short-term memory networks (LSTM) and evaluate our proposed approach on four sets of two-speaker mixtures from extended Danish hearing in noise (HINT) dataset. We show that the proposed loss function can offer improved or at par objective intelligibility (in terms of ESTOI) compared to an MSE optimized baseline while resulting in lower objective separation performance (in terms of the source to distortion ratio (SDR)). We then proceed to propose an approach where the network is first initialized with weights optimized for MSE criterion and then trained with the proposed ESTOI loss criterion. This approach mitigates some of the losses in objective separation performance while preserving the gains in objective intelligibility.

##### Abstract (translated by Google)
均方误差（MSE）已成为当前基于深度神经网络（DNN）的语音分离技术中的损失函数的首选。在本文中，我们提出了一个新的成本函数，旨在优化扩展的短时目标可懂度（ESTOI）度量。我们专注于低算法延迟（$ \ leq 10 $ ms）非常重要的应用。我们使用长期短期记忆网络（LSTM）并评估我们提出的方法对来自扩展丹麦噪声听觉（HINT）数据集的四组双扬声器混合。我们表明，与MSE优化基线相比，所提出的损失函数可以提供改进的或相似的客观可懂度（就ESTOI而言），同时导致较低的客观分离性能（就源与失真比（SDR）而言）。然后，我们继续提出一种方法，首先使用针对MSE标准优化的权重初始化网络，然后使用所提出的ESTOI损失标准进行训练。这种方法减轻了客观分离性能的一些损失，同时保留了客观可懂度的增益。

##### URL
[https://arxiv.org/abs/1807.06899](https://arxiv.org/abs/1807.06899)

##### PDF
[https://arxiv.org/pdf/1807.06899](https://arxiv.org/pdf/1807.06899)

