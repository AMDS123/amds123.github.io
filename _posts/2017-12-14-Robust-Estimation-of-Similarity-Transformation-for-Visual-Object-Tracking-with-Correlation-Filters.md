---
layout: post
title: "Robust Estimation of Similarity Transformation for Visual Object Tracking with Correlation Filters"
date: 2017-12-14 14:09:36
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Prediction Relation
author: Yang Li, Jianke Zhu, Wenjie Song, Zhefeng Wang, Hantang Liu, Steven C.H. Hoi
mathjax: true
---

* content
{:toc}

##### Abstract
Most of existing correlation filter-based tracking approaches only estimate simple axis-aligned bounding boxes, and very few of them is capable of recovering the underlying similarity transformation. To a large extent, such limitation restricts the applications of such trackers for a wide range of scenarios. In this paper, we propose a novel correlation filter-based tracker with robust estimation of similarity transformation on the large displacements to tackle this challenging problem. In order to efficiently search in such a large 4-DoF space in real-time, we formulate the problem into two 2-DoF sub-problems and apply an efficient Block Coordinates Descent solver to optimize the estimation result. Specifically, we employ an efficient phase correlation scheme to deal with both scale and rotation changes simultaneously in log-polar coordinates. Moreover, a fast variant of correlation filter is used to predict the translational motion individually. Our experimental results demonstrate that the proposed tracker achieves very promising prediction performance compared with the state-of-the-art visual object tracking methods while still retaining the advantages of efficiency and simplicity in conventional correlation filter-based tracking methods.

##### Abstract (translated by Google)
目前大多数基于相关滤波器的跟踪方法只能估计简单的轴对齐边界框，其中很少有能够恢复潜在的相似性转换。这种限制在很大程度上限制了这种跟踪器在各种情况下的应用。在本文中，我们提出了一种新的基于相关滤波器的跟踪器，在大位移的鲁棒性相似变换的估计，以解决这个具有挑战性的问题。为了有效地在这样一个大的4-DoF空间中进行实时搜索，我们将问题转化为两个2-DoF子问题，并应用一个高效的块坐标下降求解器来优化估计结果。具体来说，我们采用一个有效的相位相关方案来同时处理对数极坐标中的尺度和旋转变化。而且，使用相关滤波器的快速变体来单独预测平移运动。我们的实验结果表明，与现有技术的视觉对象跟踪方法相比，所提出的跟踪器实现了非常有希望的预测性能，同时仍然保留了传统的基于相关滤波器的跟踪方法中的效率和简单性的优点。

##### URL
[http://arxiv.org/abs/1712.05231](http://arxiv.org/abs/1712.05231)

##### PDF
[http://arxiv.org/pdf/1712.05231](http://arxiv.org/pdf/1712.05231)

