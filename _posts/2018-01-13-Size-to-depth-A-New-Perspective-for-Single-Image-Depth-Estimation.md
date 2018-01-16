---
layout: post
title: "Size-to-depth: A New Perspective for Single Image Depth Estimation"
date: 2018-01-13 16:14:42
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization Relation
author: Yiran Wu, Sihao Ying, Lianmin Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we consider the problem of single monocular image depth estimation. It is a challenging problem due to its ill-posedness nature and has found wide application in industry. Previous efforts belongs roughly to two families: learning-based method and interactive method. Learning-based method, in which deep convolutional neural network (CNN) is widely used, can achieve good result. But they suffer low generalization ability and typically perform poorly for unfamiliar scenes. Besides, data-hungry nature for such method makes data aquisition expensive and time-consuming. Interactive method requires human annotation of depth which, however, is errorneous and of large variance. To overcome these problems, we propose a new perspective for single monocular image depth estimation problem: size to depth. Our method require sparse label for real-world size of object rather than raw depth. A Coarse depth map is then inferred following geometric relationships according to size labels. Then we refine the depth map by doing energy function optimization on conditional random field(CRF). We experimentally demonstrate that our method outperforms traditional depth-labeling methods and can produce satisfactory depth maps.

##### Abstract (translated by Google)
在本文中，我们考虑单眼图像深度估计的问题。这是一个具有挑战性的问题，由于它的不适性而在工业中得到了广泛的应用。以前的努力大致分为两大类：基于学习的方法和交互方法。深度卷积神经网络（CNN）应用广泛的基于学习的方法可以取得较好的效果。但是他们的泛化能力很低，对陌生的场景通常表现不佳。此外，这种方法的数据饥饿性质使数据获取花费昂贵和耗时。交互式方法需要深度的人类注释，然而，这是错误的和大的方差。为了克服这些问题，我们提出了一个单视点图像深度估计问题的新视角：尺寸到深度。我们的方法要求对象的实际尺寸的稀疏标签而不是粗糙的深度。然后根据尺寸标签在几何关系之后推断粗糙深度图。然后通过对条件随机场（CRF）进行能量函数优化来完善深度图。我们通过实验证明，我们的方法胜过传统的深度标注方法，并且可以生成令人满意的深度图。

##### URL
[https://arxiv.org/abs/1801.04461](https://arxiv.org/abs/1801.04461)

##### PDF
[https://arxiv.org/pdf/1801.04461](https://arxiv.org/pdf/1801.04461)

