---
layout: post
title: "Compensating for Large In-Plane Rotations in Natural Images"
date: 2016-11-17 15:50:36
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Optimization
author: Lokesh Boominathan, Suraj Srinivas, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Rotation invariance has been studied in the computer vision community primarily in the context of small in-plane rotations. This is usually achieved by building invariant image features. However, the problem of achieving invariance for large rotation angles remains largely unexplored. In this work, we tackle this problem by directly compensating for large rotations, as opposed to building invariant features. This is inspired by the neuro-scientific concept of mental rotation, which humans use to compare pairs of rotated objects. Our contributions here are three-fold. First, we train a Convolutional Neural Network (CNN) to detect image rotations. We find that generic CNN architectures are not suitable for this purpose. To this end, we introduce a convolutional template layer, which learns representations for canonical 'unrotated' images. Second, we use Bayesian Optimization to quickly sift through a large number of candidate images to find the canonical 'unrotated' image. Third, we use this method to achieve robustness to large angles in an image retrieval scenario. Our method is task-agnostic, and can be used as a pre-processing step in any computer vision system.

##### Abstract (translated by Google)
计算机视觉领域的旋转不变性主要是在小面内旋转的情况下进行的。这通常通过建立不变的图像特征来实现。然而，大旋转角度实现不变性的问题在很大程度上仍然是未知的。在这项工作中，我们通过直接补偿大的旋转来解决这个问题，而不是建立不变的特征。这是灵感来自心理旋转的神经科学概念，人类用它来比较旋转对象的对。我们的贡献有三重。首先，我们训练一个卷积神经网络（CNN）来检测图像旋转。我们发现通用的CNN架构不适合这个目的。为此，我们引入一个卷积模板层，学习典型“未旋转”图像的表示。其次，我们使用贝叶斯优化快速筛选大量的候选图像，以找到规范的“未旋转”图像。第三，我们使用这种方法在图像检索场景中实现对大角度的鲁棒性。我们的方法是与任务无关的，可以在任何计算机视觉系统中用作预处理步骤。

##### URL
[https://arxiv.org/abs/1611.05744](https://arxiv.org/abs/1611.05744)

##### PDF
[https://arxiv.org/pdf/1611.05744](https://arxiv.org/pdf/1611.05744)

