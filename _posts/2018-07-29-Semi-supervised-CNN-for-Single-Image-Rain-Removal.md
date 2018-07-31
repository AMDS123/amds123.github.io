---
layout: post
title: "Semi-supervised CNN for Single Image Rain Removal"
date: 2018-07-29 16:31:40
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Wei Wei, Deyu Meng, Qian Zhao, Zongben Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Single image rain removal is a typical inverse problem in computer vision. The deep learning technique has been verified to be effective to this task and achieved state-of-the-art performance. However, the method needs to pre-collect a large set of image pairs with/without rains for training, which not only makes the method laborsome to be practically implemented, but also tends to make the trained network bias to the training samples while less generalized to test samples with unseen rain types in training. To this issue, this paper firstly proposes a semisupervised learning paradigm to this task. Different from traditional deep learning methods which use only supervised image pairs with/without rains, we put the real rainy images, without need of their clean ones, into the network training process as well. This is realized by elaborately formulating the residual between an input rainy image and its expected network output (clear image without rains) as a concise patch-wised Mixture of Gaussians distribution. The entire objective function for training network is thus the combination of the supervised data loss (least square loss between input clear image and the network output) and the unsupervised data loss. In this way, all such unsupervised rainy images, which is much easier to collect than supervised ones, can be rationally fed into the network training process, and thus both the short-of-training-sample and bias-to-supervised-sample issues can be evidently alleviated. Experiments implemented on synthetic and real data experiments verify the superiority of our model as compared to the state-of-the-arts.

##### Abstract (translated by Google)
单图像雨水去除是计算机视觉中的典型逆问题。深度学习技术已被证实对此任务有效并且实现了最先进的性能。然而，该方法需要预先收集大量具有/不具有降雨量的图像对用于训练，这不仅使得该方法实际上实际应用，而且还倾向于使训练的网络偏向于训练样本而不是一般化在训练中测试看不见的雨水样本。对于这个问题，本文首先提出了一种半监督学习范式来完成这项任务。与传统的深度学习方法不同，传统的深度学习方法只使用带有/不带有雨水的监督图像对，我们将真实的雨季图像，不需要干净的图像，也放入网络训练过程中。这是通过精心制定输入雨天图像与其预期网络输出（没有降雨的清晰图像）之间的残差来实现的，作为简洁的补丁 - 高斯混合分布。因此，训练网络的整个目标函数是监督数据丢失（输入清晰图像和网络输出之间的最小平方损失）和无监督数据丢失的组合。通过这种方式，所有这些无监督的雨天图像比监督的图像更容易收集，可以合理地输入到网络训练过程中，从而导致训练样本不足和偏向监督样本问题。可以明显减轻。在合成和真实数据实验上实施的实验验证了我们的模型与现有技术相比的优越性。

##### URL
[http://arxiv.org/abs/1807.11078](http://arxiv.org/abs/1807.11078)

##### PDF
[http://arxiv.org/pdf/1807.11078](http://arxiv.org/pdf/1807.11078)

