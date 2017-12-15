---
layout: post
title: "Top-Down Learning for Structured Labeling with Convolutional Pseudoprior"
date: 2016-07-26 05:25:29
categories: arXiv_CV
tags: arXiv_CV CNN Inference RNN
author: Saining Xie, Xun Huang, Zhuowen Tu
mathjax: true
---

* content
{:toc}

##### Abstract
Current practice in convolutional neural networks (CNN) remains largely bottom-up and the role of top-down process in CNN for pattern analysis and visual inference is not very clear. In this paper, we propose a new method for structured labeling by developing convolutional pseudo-prior (ConvPP) on the ground-truth labels. Our method has several interesting properties: (1) compared with classical machine learning algorithms like CRFs and Structural SVM, ConvPP automatically learns rich convolutional kernels to capture both short- and long- range contexts; (2) compared with cascade classifiers like Auto-Context, ConvPP avoids the iterative steps of learning a series of discriminative classifiers and automatically learns contextual configurations; (3) compared with recent efforts combing CNN models with CRFs and RNNs, ConvPP learns convolution in the labeling space with much improved modeling capability and less manual specification; (4) compared with Bayesian models like MRFs, ConvPP capitalizes on the rich representation power of convolution by automatically learning priors built on convolutional filters. We accomplish our task using pseudo-likelihood approximation to the prior under a novel fixed-point network structure that facilitates an end-to-end learning process. We show state-of-the-art results on sequential labeling and image labeling benchmarks.

##### Abstract (translated by Google)
卷积神经网络（CNN）目前的实践仍然基本上是自下而上的，而自上而下的CNN模式分析和视觉推理的作用还不是很清楚。在本文中，我们通过在地面真值标签上开发卷积伪先验（ConvPP）来提出一种结构化标签的新方法。我们的方法有以下几个有趣的特性：（1）与经典的机器学习算法（如CRF和结构SVM）相比，ConvPP自动学习丰富的卷积核来捕获短期和长期的上下文; （2）与Auto-Context等级联分类器相比，ConvPP避免了学习一系列判别分类器和自动学习上下文配置的迭代步骤; （3）与最近CNN模型与CRF和RNN结合的努力相比，ConvPP在标签空间中学习卷积，建模能力大大提高，手工规范少; （4）与像MRF这样的贝叶斯模型相比，ConvPP通过自动学习基于卷积滤波器的先验来充分利用卷积丰富的表示能力。我们在一个新颖的定点网络结构下利用伪似然近似来完成我们的任务，从而促进了端到端的学习过程。我们展示了顺序标签和图像标签基准的最新成果。

##### URL
[https://arxiv.org/abs/1511.07409](https://arxiv.org/abs/1511.07409)

##### PDF
[https://arxiv.org/pdf/1511.07409](https://arxiv.org/pdf/1511.07409)

