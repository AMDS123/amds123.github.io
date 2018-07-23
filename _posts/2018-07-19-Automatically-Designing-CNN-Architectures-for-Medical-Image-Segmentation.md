---
layout: post
title: "Automatically Designing CNN Architectures for Medical Image Segmentation"
date: 2018-07-19 23:47:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning
author: Aliasghar Mortazi, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network architectures have traditionally been designed and explored with human expertise in a long-lasting trial-and-error process. This process requires huge amount of time, expertise, and resources. To address this tedious problem, we propose a novel algorithm to optimally find hyperparameters of a deep network architecture automatically. We specifically focus on designing neural architectures for medical image segmentation task. Our proposed method is based on a policy gradient reinforcement learning for which the reward function is assigned a segmentation evaluation utility (i.e., dice index). We show the efficacy of the proposed method with its low computational cost in comparison with the state-of-the-art medical image segmentation networks. We also present a new architecture design, a densely connected encoder-decoder CNN, as a strong baseline architecture to apply the proposed hyperparameter search algorithm. We apply the proposed algorithm to each layer of the baseline architectures. As an application, we train the proposed system on cine cardiac MR images from Automated Cardiac Diagnosis Challenge (ACDC) MICCAI 2017. Starting from a baseline segmentation architecture, the resulting network architecture obtains the state-of-the-art results in accuracy without performing any trial-and-error based architecture design approaches or close supervision of the hyperparameters changes.

##### Abstract (translated by Google)
传统上，深度神经网络架构是在持久的试错过程中利用人类专业知识进行设计和探索的。这个过程需要大量的时间，专业知识和资源。为了解决这个繁琐的问题，我们提出了一种新的算法来自动地优化深度网络架构的超参数。我们专注于为医学图像分割任务设计神经架构。我们提出的方法基于策略梯度强化学习，其中奖励函数被分配了分段评估实用程序（即，骰子索引）。与现有技术的医学图像分割网络相比，我们以低计算成本显示了所提出方法的功效。我们还提出了一种新的架构设计，一种密集连接的编码器 - 解码器CNN，作为应用所提出的超参数搜索算法的强基线架构。我们将提出的算法应用于基线架构的每一层。作为一项应用，我们根据自动心脏诊断挑战赛（ACDC）MICCAI 2017对电影心脏MR图像进行训练。从基线分割架构开始，最终的网络架构在不执行的情况下获得最先进的精确结果任何基于试验和错误的架构设计方法或对超参数变化的密切监督。

##### URL
[http://arxiv.org/abs/1807.07663](http://arxiv.org/abs/1807.07663)

##### PDF
[http://arxiv.org/pdf/1807.07663](http://arxiv.org/pdf/1807.07663)

