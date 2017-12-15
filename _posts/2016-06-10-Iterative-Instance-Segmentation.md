---
layout: post
title: "Iterative Instance Segmentation"
date: 2016-06-10 18:48:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference Prediction
author: Ke Li, Bharath Hariharan, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods for pixel-wise labelling tasks generally disregard the underlying structure of labellings, often leading to predictions that are visually implausible. While incorporating structure into the model should improve prediction quality, doing so is challenging - manually specifying the form of structural constraints may be impractical and inference often becomes intractable even if structural constraints are given. We sidestep this problem by reducing structured prediction to a sequence of unconstrained prediction problems and demonstrate that this approach is capable of automatically discovering priors on shape, contiguity of region predictions and smoothness of region contours from data without any a priori specification. On the instance segmentation task, this method outperforms the state-of-the-art, achieving a mean $\mathrm{AP}^{r}$ of 63.6% at 50% overlap and 43.3% at 70% overlap.

##### Abstract (translated by Google)
像素标签任务的现有方法通常忽略标签的底层结构，往往导致预测在视觉上不可信。虽然将模型纳入模型可以提高预测质量，但是这样做是具有挑战性的 - 手动指定结构约束的形式可能是不切实际的，即使给出了结构约束，推理也往往变得棘手。我们通过将结构化预测减少为一系列无约束的预测问题来回避这个问题，并且证明这种方法能够在没有任何先验规范的情况下自动发现形状上的先验，区域预测的邻接性和区域轮廓的平滑性。在实例分割任务中，这种方法胜过了现有技术，在50％重叠的情况下获得了63.6％的平均$ \ mathrm {AP} ^ {r} $，在70％的重叠时达到了43.3％。

##### URL
[https://arxiv.org/abs/1511.08498](https://arxiv.org/abs/1511.08498)

##### PDF
[https://arxiv.org/pdf/1511.08498](https://arxiv.org/pdf/1511.08498)

