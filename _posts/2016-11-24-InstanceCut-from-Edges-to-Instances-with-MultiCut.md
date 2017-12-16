---
layout: post
title: "InstanceCut: from Edges to Instances with MultiCut"
date: 2016-11-24 17:54:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Detection
author: Alexander Kirillov, Evgeny Levinkov, Bjoern Andres, Bogdan Savchynskyy, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the task of instance-aware semantic segmentation. Our key motivation is to design a simple method with a new modelling-paradigm, which therefore has a different trade-off between advantages and disadvantages compared to known approaches. Our approach, we term InstanceCut, represents the problem by two output modalities: (i) an instance-agnostic semantic segmentation and (ii) all instance-boundaries. The former is computed from a standard convolutional neural network for semantic segmentation, and the latter is derived from a new instance-aware edge detection model. To reason globally about the optimal partitioning of an image into instances, we combine these two modalities into a novel MultiCut formulation. We evaluate our approach on the challenging CityScapes dataset. Despite the conceptual simplicity of our approach, we achieve the best result among all published methods, and perform particularly well for rare object classes.

##### Abstract (translated by Google)
这项工作解决了实例感知语义分割的任务。我们的主要动机是设计一个新的建模范例的简单方法，因此与已知方法相比，它在优缺点之间具有不同的折衷。我们的方法，我们称为InstanceCut，用两种输出模式来表示问题：（i）不依赖于实例的语义分割和（ii）所有的实例边界。前者是从一个标准的卷积神经网络进行语义分割计算而来的，后者是从一个新的实例感知的边缘检测模型导出的。为了全局推理图像的最佳分割为实例，我们将这两种模式组合成一种新颖的MultiCut公式。我们在具有挑战性的CityScapes数据集上评估我们的方法。尽管我们的方法在概念上很简单，但是我们在所有已发布的方法中取得了最好的结果，并且对罕见的对象类表现得特别好。

##### URL
[https://arxiv.org/abs/1611.08272](https://arxiv.org/abs/1611.08272)

##### PDF
[https://arxiv.org/pdf/1611.08272](https://arxiv.org/pdf/1611.08272)

