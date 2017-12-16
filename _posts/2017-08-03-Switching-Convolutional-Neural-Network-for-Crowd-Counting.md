---
layout: post
title: "Switching Convolutional Neural Network for Crowd Counting"
date: 2017-08-03 11:02:02
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Deepak Babu Sam, Shiv Surya, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel crowd counting model that maps a given crowd scene to its density. Crowd analysis is compounded by myriad of factors like inter-occlusion between people due to extreme crowding, high similarity of appearance between people and background elements, and large variability of camera view-points. Current state-of-the art approaches tackle these factors by using multi-scale CNN architectures, recurrent networks and late fusion of features from multi-column CNN with different receptive fields. We propose switching convolutional neural network that leverages variation of crowd density within an image to improve the accuracy and localization of the predicted crowd count. Patches from a grid within a crowd scene are relayed to independent CNN regressors based on crowd count prediction quality of the CNN established during training. The independent CNN regressors are designed to have different receptive fields and a switch classifier is trained to relay the crowd scene patch to the best CNN regressor. We perform extensive experiments on all major crowd counting datasets and evidence better performance compared to current state-of-the-art methods. We provide interpretable representations of the multichotomy of space of crowd scene patches inferred from the switch. It is observed that the switch relays an image patch to a particular CNN column based on density of crowd.

##### Abstract (translated by Google)
我们提出了一个新的人群计数模型，将给定的人群场景映射到密度。人群分析由多种因素混杂在一起，例如由于极度拥挤而导致人与人之间的遮挡，人与背景元素之间的高度相似性以及摄像机视点的巨大变化。当前最先进的方法通过使用多尺度CNN架构，经常性网络和来自具有不同感受域的多列CNN的特征的后期融合来解决这些因素。我们建议切换卷积神经网络，利用图像内人群密度的变化来提高预测人群数量的准确性和本地化。根据在训练期间建立的CNN的人数预测质量，来自人群场景中的网格的补丁被转发给独立的CNN回归器。独立的CNN回归器被设计为具有不同的接受场，并且开关分类器被训练以将人群场景片补充到最好的CNN回归器。我们对所有主要的人群计数数据集进行了广泛的实验，证明与当前最先进的方法相比有更好的性能。我们提供从开关推断出的人群场景片的空间多重性的可解释表示。据观察，交换机根据人群密度将图像块转发到特定的CNN列。

##### URL
[https://arxiv.org/abs/1708.00199](https://arxiv.org/abs/1708.00199)

##### PDF
[https://arxiv.org/pdf/1708.00199](https://arxiv.org/pdf/1708.00199)

