---
layout: post
title: "W-net: Bridged U-net for 2D Medical Image Segmentation"
date: 2018-07-12 08:08:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction
author: Wanli Chen, Yue Zhang, Junjun He, Yu Qiao, Yifan Chen, Hongjian Shi, Xiaoying Tang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we focus on three problems in deep learning based medical image segmentation. Firstly, U-net, as a popular model for medical image segmentation, is difficult to train when convolutional layers increase even though a deeper network usually has a better generalization ability because of more learnable parameters. Secondly, the exponential ReLU (ELU), as an alternative of ReLU, is not much different from ReLU when the network of interest gets deep. Thirdly, the Dice loss, as one of the pervasive loss functions for medical image segmentation, is not effective when the prediction is close to ground truth and will cause oscillation during training. To address the aforementioned three problems, we propose and validate a deeper network that can fit medical image datasets that are usually small in the sample size. Meanwhile, we propose a new loss function to accelerate the learning process and a combination of different activation functions to improve the network performance. Our experimental results suggest that our network is comparable or superior to state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们关注基于深度学习的医学图像分割中的三个问题。首先，作为医学图像分割的流行模型，U-net在卷积层增加时难以训练，即使更深的网络通常由于更多可学习的参数而具有更好的泛化能力。其次，作为ReLU的替代方案，指数ReLU（ELU）与感兴趣的网络深入时的ReLU没有太大差别。第三，作为医学图像分割的普遍损失函数之一的骰子损失在预测接近基础事实并且在训练期间将引起振荡时是无效的。为了解决上述三个问题，我们提出并验证了一个更深入的网络，该网络可以适合通常样本量较小的医学图像数据集。同时，我们提出了一种新的损失功能，以加速学习过程和不同激活功能的组合，以提高网络性能。我们的实验结果表明，我们的网络与最先进的方法相当或更优越。

##### URL
[http://arxiv.org/abs/1807.04459](http://arxiv.org/abs/1807.04459)

##### PDF
[http://arxiv.org/pdf/1807.04459](http://arxiv.org/pdf/1807.04459)

