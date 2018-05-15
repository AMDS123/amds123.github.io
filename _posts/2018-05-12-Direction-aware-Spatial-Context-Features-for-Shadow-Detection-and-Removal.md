---
layout: post
title: "Direction-aware Spatial Context Features for Shadow Detection and Removal"
date: 2018-05-12 02:15:42
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Detection
author: Xiaowei Hu, Chi-Wing Fu, Lei Zhu, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Shadow detection and shadow removal are fundamental and challenging tasks, requiring an understanding of the global image semantics. This paper presents a novel deep neural network design for shadow detection and removal by analyzing the image context in a direction-aware manner. To achieve this, we first formulate the direction-aware attention mechanism in a spatial recurrent neural network (RNN) by introducing attention weights when aggregating spatial context features in the RNN. By learning these weights through training, we can recover direction-aware spatial context (DSC) for detecting and removing shadows. This design is developed into the DSC module and embedded in a convolutional neural network (CNN) to learn the DSC features in different levels. Moreover, we design a weighted cross entropy loss to make effective the training for shadow detection and further adopt the network for shadow removal by using a Euclidean loss function and formulating a color transfer function to address the color and luminosity inconsistency in the training pairs. We employ two shadow detection benchmark datasets and two shadow removal benchmark datasets, and perform various experiments to evaluate our method. Experimental results show that our method clearly outperforms state-of-the-art methods for both shadow detection and shadow removal.

##### Abstract (translated by Google)
阴影检测和阴影消除是基本和具有挑战性的任务，需要了解全局图像语义。本文提出了一种新的深度神经网络设计阴影检测和去除通过分析方向感知方式的图像上下文。为了实现这个目标，我们首先通过在RNN中聚合空间环境特征时引入注意力权重来在空间递归神经网络（RNN）中制定方向感知关注机制。通过训练学习这些权重，我们可以恢复方向感知空间上下文（DSC）来检测和消除阴影。这种设计被开发成DSC模块并嵌入到卷积神经网络（CNN）中以学习不同层次的DSC特征。此外，我们设计了一个加权交叉熵损失，使阴影检测的训练更加有效，并通过使用欧几里德损失函数和制定颜色传递函数来进一步采用网络去除阴影，以解决训练对中的颜色和亮度不一致问题。我们使用两个阴影检测基准数据集和两个阴影去除基准数据集，并执行各种实验来评估我们的方法。实验结果表明，我们的方法明显优于最新的阴影检测和阴影去除方法。

##### URL
[https://arxiv.org/abs/1805.04635](https://arxiv.org/abs/1805.04635)

##### PDF
[https://arxiv.org/pdf/1805.04635](https://arxiv.org/pdf/1805.04635)

