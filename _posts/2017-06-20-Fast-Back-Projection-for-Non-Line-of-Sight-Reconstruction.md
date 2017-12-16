---
layout: post
title: "Fast Back-Projection for Non-Line of Sight Reconstruction"
date: 2017-06-20 11:02:49
categories: arXiv_CV
tags: arXiv_CV
author: Victor Arellano, Diego Gutierrez, Adrian Jarabo
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works have demonstrated non-line of sight (NLOS) reconstruction by using the time-resolved signal frommultiply scattered light. These works combine ultrafast imaging systems with computation, which back-projects the recorded space-time signal to build a probabilistic map of the hidden geometry. Unfortunately, this computation is slow, becoming a bottleneck as the imaging technology improves. In this work, we propose a new back-projection technique for NLOS reconstruction, which is up to a thousand times faster than previous work, with almost no quality loss. We base on the observation that the hidden geometry probability map can be built as the intersection of the three-bounce space-time manifolds defined by the light illuminating the hidden geometry and the visible point receiving the scattered light from such hidden geometry. This allows us to pose the reconstruction of the hidden geometry as the voxelization of these space-time manifolds, which has lower theoretic complexity and is easily implementable in the GPU. We demonstrate the efficiency and quality of our technique compared against previous methods in both captured and synthetic data

##### Abstract (translated by Google)
最近的工作已经通过使用来自多重散射光的时间分辨信号来证明非视线（NLOS）重构。这些作品将超快成像系统与计算相结合，后者对记录的时空信号进行反投影，以建立隐藏几何图形的概率图。不幸的是，这个计算速度很慢，随着成像技术的提高，成为一个瓶颈。在这项工作中，我们提出了一种新的NLOS重建背投技术，比以前的工作快了上千倍，几乎没有质量损失。我们基于这样的观察，即隐藏的几何概率图可以被建立为由反射隐藏的几何的光所定义的三次反射的时空流形与接收来自这种隐藏的几何的散射光的可见点的交集。这使得我们可以将隐藏几何体的重建形成为这些空时流形的体素化，其具有较低的理论复杂度并且易于在GPU中实现。我们证明了我们的技术在捕获和合成数据中与以前的方法相比的效率和质量

##### URL
[https://arxiv.org/abs/1703.02016](https://arxiv.org/abs/1703.02016)

##### PDF
[https://arxiv.org/pdf/1703.02016](https://arxiv.org/pdf/1703.02016)

