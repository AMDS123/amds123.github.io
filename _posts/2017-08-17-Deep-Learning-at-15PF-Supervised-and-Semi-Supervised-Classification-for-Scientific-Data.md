---
layout: post
title: "Deep Learning at 15PF: Supervised and Semi-Supervised Classification for Scientific Data"
date: 2017-08-17 13:21:36
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Thorsten Kurth, Jian Zhang, Nadathur Satish, Ioannis Mitliagkas, Evan Racah, Mostofa Ali Patwary, Tareq Malas, Narayanan Sundaram, Wahid Bhimji, Mikhail Smorkalov, Jack Deslippe, Mikhail Shiryaev, Srinivas Sridharan, Prabhat, Pradeep Dubey
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the first, 15-PetaFLOP Deep Learning system for solving scientific pattern classification problems on contemporary HPC architectures. We develop supervised convolutional architectures for discriminating signals in high-energy physics data as well as semi-supervised architectures for localizing and classifying extreme weather in climate data. Our Intelcaffe-based implementation obtains $\sim$2TFLOP/s on a single Cori Phase-II Xeon-Phi node. We use a hybrid strategy employing synchronous node-groups, while using asynchronous communication across groups. We use this strategy to scale training of a single model to $\sim$9600 Xeon-Phi nodes; obtaining peak performance of 11.73-15.07 PFLOP/s and sustained performance of 11.41-13.27 PFLOP/s. At scale, our HEP architecture produces state-of-the-art classification accuracy on a dataset with 10M images, exceeding that achieved by selections on high-level physics-motivated features. Our semi-supervised architecture successfully extracts weather patterns in a 15TB climate dataset. Our results demonstrate that Deep Learning can be optimized and scaled effectively on many-core, HPC systems.

##### Abstract (translated by Google)
本文介绍了第一个15-PetaFLOP深度学习系统，用于解决当前HPC架构的科学模式分类问题。我们开发监督卷积体系结构，用于区分高能物理数据中的信号以及用于定位和分类气候数据中极端天气的半监督体系结构。基于Intelcaffe的实现在单个Cori Phase-II Xeon-Phi节点上获得$ \ sim $ 2TFLOP / s。我们使用采用同步节点组的混合策略，而跨组使用异步通信。我们使用这个策略将单个模型的训练扩展到$ \ sim $ 9600 Xeon-Phi节点;获得11.73-15.07 PFLOP / s的峰值性能和11.41-13.27 PFLOP / s的持续性能。在规模上，我们的HEP架构能够在具有10M图像的数据集上产生最先进的分类精度，超过了高级物理驱动功能的选择。我们的半监督式建筑成功地提取了15TB气候数据集中的天气模式。我们的研究结果表明，深度学习可以在多核高性能计算系统上进行优化和有效扩展。

##### URL
[https://arxiv.org/abs/1708.05256](https://arxiv.org/abs/1708.05256)

##### PDF
[https://arxiv.org/pdf/1708.05256](https://arxiv.org/pdf/1708.05256)

