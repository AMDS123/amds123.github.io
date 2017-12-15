---
layout: post
title: "A Coarse-to-Fine Indoor Layout Estimation Method"
date: 2016-07-03 05:55:47
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization
author: Yuzhuo Ren, Chen Chen, Shangwen Li, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
The task of estimating the spatial layout of cluttered indoor scenes from a single RGB image is addressed in this work. Existing solutions to this problems largely rely on hand-craft features and vanishing lines, and they often fail in highly cluttered indoor rooms. The proposed coarse-to-fine indoor layout estimation (CFILE) method consists of two stages: 1) coarse layout estimation; and 2) fine layout localization. In the first stage, we adopt a fully convolutional neural network (FCN) to obtain a coarse-scale room layout estimate that is close to the ground truth globally. The proposed FCN considers combines the layout contour property and the surface property so as to provide a robust estimate in the presence of cluttered objects. In the second stage, we formulate an optimization framework that enforces several constraints such as layout contour straightness, surface smoothness and geometric constraints for layout detail refinement. Our proposed system offers the state-of-the-art performance on two commonly used benchmark datasets.

##### Abstract (translated by Google)
本文研究了从一幅RGB图像估计杂乱室内场景的空间布局的任务。这个问题的现有解决方案在很大程度上依赖于手工工艺特征和消失的线条，并且在高度混乱的室内房间中经常失败。所提出的从粗到精的室内布局估计（CFILE）方法包括两个阶段：1）粗略布局估计;和2）精细的布局本地化。在第一阶段，我们采用完全卷积神经网络（FCN）来获得全局接近于地面真实的粗尺度房间布局估计。建议的FCN考虑将布局等值特性和表面特性相结合，以便在存在杂乱物体的情况下提供可靠的估计。在第二阶段，我们制定了一个优化框架，强化布局轮廓直线度，表面平滑度和几何约束等几个约束条件来优化布局细节。我们提出的系统在两个常用的基准数据集上提供了最先进的性能。

##### URL
[https://arxiv.org/abs/1607.00598](https://arxiv.org/abs/1607.00598)

##### PDF
[https://arxiv.org/pdf/1607.00598](https://arxiv.org/pdf/1607.00598)

