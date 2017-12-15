---
layout: post
title: "Learning Spatially Regularized Correlation Filters for Visual Tracking"
date: 2016-08-19 11:11:49
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking Optimization Relation
author: Martin Danelljan, Gustav Häger, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
Robust and accurate visual tracking is one of the most challenging computer vision problems. Due to the inherent lack of training data, a robust approach for constructing a target appearance model is crucial. Recently, discriminatively learned correlation filters (DCF) have been successfully applied to address this problem for tracking. These methods utilize a periodic assumption of the training samples to efficiently learn a classifier on all patches in the target neighborhood. However, the periodic assumption also introduces unwanted boundary effects, which severely degrade the quality of the tracking model. We propose Spatially Regularized Discriminative Correlation Filters (SRDCF) for tracking. A spatial regularization component is introduced in the learning to penalize correlation filter coefficients depending on their spatial location. Our SRDCF formulation allows the correlation filters to be learned on a significantly larger set of negative training samples, without corrupting the positive samples. We further propose an optimization strategy, based on the iterative Gauss-Seidel method, for efficient online learning of our SRDCF. Experiments are performed on four benchmark datasets: OTB-2013, ALOV++, OTB-2015, and VOT2014. Our approach achieves state-of-the-art results on all four datasets. On OTB-2013 and OTB-2015, we obtain an absolute gain of 8.0% and 8.2% respectively, in mean overlap precision, compared to the best existing trackers.

##### Abstract (translated by Google)
健壮和准确的视觉跟踪是最具挑战性的计算机视觉问题之一。由于内在缺乏训练数据，构建目标外观模型的稳健方法至关重要。最近，差分学习相关滤波器（DCF）已被成功应用于解决这个跟踪问题。这些方法利用训练样本的周期性假设来有效地学习目标邻域中的所有片上的分类器。然而，周期性的假设也引入了不必要的边界效应，严重降低了跟踪模型的质量。我们提出空间正则化判别相关滤波器（SRDCF）进行跟踪。在学习中引入空间正则化分量以根据其空间位置对相关滤波器系数进行惩罚。我们的SRDCF公式允许在相当大的一组负值训练样本上学习相关滤波器，而不会破坏正样本。我们进一步提出了一种基于迭代Gauss-Seidel方法的优化策略，用于SRDCF的高效在线学习。在四个基准数据集上进行实验：OTB-2013，ALOV ++，OTB-2015和VOT2014。我们的方法在所有四个数据集上实现了最先进的结果。在OTB-2013和OTB-2015中，平均重叠精度分别比现有最好的跟踪器分别获得了8.0％和8.2％的绝对收益。

##### URL
[https://arxiv.org/abs/1608.05571](https://arxiv.org/abs/1608.05571)

##### PDF
[https://arxiv.org/pdf/1608.05571](https://arxiv.org/pdf/1608.05571)

