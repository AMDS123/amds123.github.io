---
layout: post
title: "weedNet: Dense Semantic Weed Classification Using Multispectral Images and MAV for Smart Farming"
date: 2017-09-11 10:59:01
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Inkyu Sa, Zetao Chen, Marija Popovic, Raghav Khanna, Frank Liebisch, Juan Nieto, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
Selective weed treatment is a critical step in autonomous crop management as related to crop health and yield. However, a key challenge is reliable, and accurate weed detection to minimize damage to surrounding plants. In this paper, we present an approach for dense semantic weed classification with multispectral images collected by a micro aerial vehicle (MAV). We use the recently developed encoder-decoder cascaded Convolutional Neural Network (CNN), Segnet, that infers dense semantic classes while allowing any number of input image channels and class balancing with our sugar beet and weed datasets. To obtain training datasets, we established an experimental field with varying herbicide levels resulting in field plots containing only either crop or weed, enabling us to use the Normalized Difference Vegetation Index (NDVI) as a distinguishable feature for automatic ground truth generation. We train 6 models with different numbers of input channels and condition (fine-tune) it to achieve about 0.8 F1-score and 0.78 Area Under the Curve (AUC) classification metrics. For model deployment, an embedded GPU system (Jetson TX2) is tested for MAV integration. Dataset used in this paper is released to support the community and future work.

##### Abstract (translated by Google)
选择性杂草处理是自动作物管理中与作物健康和产量相关的关键步骤。然而，一个关键的挑战是可靠的，准确的杂草检测，以尽量减少对周围植物的伤害。在本文中，我们提出了一个密集的语义杂草分类与微型飞行器（MAV）收集的多光谱图像的方法。我们使用最近开发的编码器 - 解码器级联卷积神经网络（CNN）Segnet来推断密集的语义类，同时允许任意数量的输入图像通道和类别平衡与我们的甜菜和杂草数据集。为了获得训练数据集，我们建立了一个具有不同除草剂水平的实验场，从而得到仅包含作物或杂草的田间地块，使得我们能够使用归一化差值植被指数（NDVI）作为自动地面真值生成的可区分特征。我们训练6个不同数量的输入通道和条件（微调）的模型，以达到约0.8个F1分数和0.78个曲线下面积（AUC）分类度量。对于模型部署，嵌入式GPU系统（Jetson TX2）进行MAV集成测试。本文中使用的数据集是为了支持社区和未来的工作而发布的。

##### URL
[https://arxiv.org/abs/1709.03329](https://arxiv.org/abs/1709.03329)

##### PDF
[https://arxiv.org/pdf/1709.03329](https://arxiv.org/pdf/1709.03329)

