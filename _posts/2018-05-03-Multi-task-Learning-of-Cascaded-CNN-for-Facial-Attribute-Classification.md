---
layout: post
title: "Multi-task Learning of Cascaded CNN for Facial Attribute Classification"
date: 2018-05-03 13:23:23
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Optimization Classification Detection Face_Detection
author: Ni Zhuang, Yan Yan, Si Chen, Hanzi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, facial attribute classification (FAC) has attracted significant attention in the computer vision community. Great progress has been made along with the availability of challenging FAC datasets. However, conventional FAC methods usually firstly pre-process the input images (i.e., perform face detection and alignment) and then predict facial attributes. These methods ignore the inherent dependencies among these tasks (i.e., face detection, facial landmark localization and FAC). Moreover, some methods using convolutional neural network are trained based on the fixed loss weights without considering the differences between facial attributes. In order to address the above problems, we propose a novel multi-task learning of cas- caded convolutional neural network method, termed MCFA, for predicting multiple facial attributes simultaneously. Specifically, the proposed method takes advantage of three cascaded sub-networks (i.e., S_Net, M_Net and L_Net corresponding to the neural networks under different scales) to jointly train multiple tasks in a coarse-to-fine manner, which can achieve end-to-end optimization. Furthermore, the proposed method automatically assigns the loss weight to each facial attribute based on a novel dynamic weighting scheme, thus making the proposed method concentrate on predicting the more difficult facial attributes. Experimental results show that the proposed method outperforms several state-of-the-art FAC methods on the challenging CelebA and LFWA datasets.

##### Abstract (translated by Google)
最近，面部属性分类（FAC）在计算机视觉领域引起了很大的关注。伴随着具有挑战性的FAC数据集的可用性，取得了巨大进步。然而，传统的FAC方法通常首先预处理输入图像（即，执行面部检测和对准），然后预测面部属性。这些方法忽略了这些任务之间的固有依赖关系（即人脸检测，面部标志定位和FAC）。此外，使用卷积神经网络的一些方法在不考虑面部属性差异的情况下基于固定损失权重进行训练。为了解决上述问题，我们提出了一种新型的多任务学习梯度卷积神经网络方法MCFA，用于同时预测多个面部属性。具体来说，所提出的方法利用了三个级联的子网络（即，对应于不同尺度下的神经网络的S_Net，M_Net和L_Net）以粗到细的方式联合训练多个任务，其可以实现端到端 - 优化。此外，所提出的方法基于新的动态加权方案自动地将损失权重分配给每个面部属性，从而使得所提出的方法专注于预测更困难的面部属性。实验结果表明，所提出的方法在具有挑战性的CelebA和LFWA数据集上胜过了几种最先进的FAC方法。

##### URL
[http://arxiv.org/abs/1805.01290](http://arxiv.org/abs/1805.01290)

##### PDF
[http://arxiv.org/pdf/1805.01290](http://arxiv.org/pdf/1805.01290)

