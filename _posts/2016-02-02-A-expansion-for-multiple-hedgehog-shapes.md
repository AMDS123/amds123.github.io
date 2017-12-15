---
layout: post
title: "A-expansion for multiple 'hedgehog' shapes"
date: 2016-02-02 16:42:27
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation GAN Face Optimization
author: Hossam Isack, Yuri Boykov, Olga Veksler
mathjax: true
---

* content
{:toc}

##### Abstract
Overlapping colors and cluttered or weak edges are common segmentation problems requiring additional regularization. For example, star-convexity is popular for interactive single object segmentation due to simplicity and amenability to exact graph cut optimization. This paper proposes an approach to multiobject segmentation where objects could be restricted to separate "hedgehog" shapes. We show that a-expansion moves are submodular for our multi-shape constraints. Each "hedgehog" shape has its surface normals constrained by some vector field, e.g. gradients of a distance transform for user scribbles. Tight constraint give an extreme case of a shape prior enforcing skeleton consistency with the scribbles. Wider cones of allowed normals gives more relaxed hedgehog shapes. A single click and +/-90 degrees normal orientation constraints reduce our hedgehog prior to star-convexity. If all hedgehogs come from single clicks then our approach defines multi-star prior. Our general method has significantly more applications than standard one-star segmentation. For example, in medical data we can separate multiple non-star organs with similar appearances and weak or noisy edges.

##### Abstract (translated by Google)
重叠的颜色和杂乱的或弱的边缘是常见的分割问题，需要额外的正则化。例如，对于交互式单个对象分割，由于简单和易于精确的图形切割优化，星形凸起是流行的。本文提出了一种多对象分割的方法，其中对象可以被限制为单独的“刺猬”形状。我们显示a-expansion的动作是对于我们的多形状约束的子模块。每个“刺猬”形状的表面法线都受到一些矢量场的约束。用户涂鸦的距离变换的梯度。严格的约束给出了一个极端的情况下的形状事先强调与涂鸦骨架的一致性。允许的法线的更宽的锥形给出更加宽松的刺猬形状。一个单一的点击和+ /  -  90度正常方向约束减少我们的刺猬之前，星形凸面。如果所有的刺猬都来自单一的点击，那么我们的方法定义多星级之前。我们的一般方法比标准的一星分割有更多的应用。例如，在医学数据中，我们可以分离出多个外形相似，边缘较弱或嘈杂的非星形器官。

##### URL
[https://arxiv.org/abs/1602.01006](https://arxiv.org/abs/1602.01006)

##### PDF
[https://arxiv.org/pdf/1602.01006](https://arxiv.org/pdf/1602.01006)

