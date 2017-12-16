---
layout: post
title: "Tracking Completion"
date: 2016-09-09 01:49:46
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Yao Sui, Guanghui Wang, Yafei Tang, Li Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
A fundamental component of modern trackers is an online learned tracking model, which is typically modeled either globally or locally. The two kinds of models perform differently in terms of effectiveness and robustness under different challenging situations. This work exploits the advantages of both models. A subspace model, from a global perspective, is learned from previously obtained targets via rank-minimization to address the tracking, and a pixel-level local observation is leveraged si- multaneously, from a local point of view, to augment the subspace model. A matrix completion method is employed to integrate the two models. Unlike previous tracking methods, which locate the target among all fully observed target candidates, the proposed approach first estimates an expected target via the matrix completion through partially observed target candidates, and then, identifies the target according to the estimation accuracy with respect to the target candidates. Specifically, the tracking is formulated as a problem of target appearance estimation. Extensive experiments on various challenging video sequences verify the effectiveness of the proposed approach and demonstrate that the proposed tracker outperforms other popular state-of-the-art trackers.

##### Abstract (translated by Google)
现代追踪器的基本组成部分是在线学习追踪模型，其典型地在全局或本地建模。这两种模型在不同的挑战性情况下在有效性和鲁棒性方面表现出不同的表现。这项工作利用了这两种模式的优点。从全局的角度来看，子空间模型是通过秩最小化从先前获得的目标中学习来解决跟踪问题，从局部的角度同时利用像素级的局部观察来增强子空间模型。矩阵完成方法被用来整合这两个模型。与先前在所有完全观察目标候选者中定位目标的跟踪方法不同，所提出的方法首先通过经由部分观察目标候选者的矩阵完成来估计预期目标，然后根据关于目标的估计精度来识别目标候选人。具体而言，追踪被制定为目标外观估计的问题。对各种具有挑战性的视频序列进行大量的实验验证了所提出的方法的有效性，并证明了所提出的跟踪器优于其他流行的最先进的跟踪器。

##### URL
[https://arxiv.org/abs/1608.08171](https://arxiv.org/abs/1608.08171)

##### PDF
[https://arxiv.org/pdf/1608.08171](https://arxiv.org/pdf/1608.08171)

