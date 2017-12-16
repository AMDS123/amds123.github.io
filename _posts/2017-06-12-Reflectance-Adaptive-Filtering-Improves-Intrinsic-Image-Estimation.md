---
layout: post
title: "Reflectance Adaptive Filtering Improves Intrinsic Image Estimation"
date: 2017-06-12 12:39:49
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Prediction
author: Thomas Nestmeyer, Peter V. Gehler
mathjax: true
---

* content
{:toc}

##### Abstract
Separating an image into reflectance and shading layers poses a challenge for learning approaches because no large corpus of precise and realistic ground truth decompositions exists. The Intrinsic Images in the Wild~(IIW) dataset provides a sparse set of relative human reflectance judgments, which serves as a standard benchmark for intrinsic images. A number of methods use IIW to learn statistical dependencies between the images and their reflectance layer. Although learning plays an important role for high performance, we show that a standard signal processing technique achieves performance on par with current state-of-the-art. We propose a loss function for CNN learning of dense reflectance predictions. Our results show a simple pixel-wise decision, without any context or prior knowledge, is sufficient to provide a strong baseline on IIW. This sets a competitive baseline which only two other approaches surpass. We then develop a joint bilateral filtering method that implements strong prior knowledge about reflectance constancy. This filtering operation can be applied to any intrinsic image algorithm and we improve several previous results achieving a new state-of-the-art on IIW. Our findings suggest that the effect of learning-based approaches may have been over-estimated so far. Explicit prior knowledge is still at least as important to obtain high performance in intrinsic image decompositions.

##### Abstract (translated by Google)
将图像分离成反射和阴影图层对于学习方法提出了挑战，因为不存在大量精确和现实的地面真实分解的语料库。 Wild〜（IIW）数据集中的内在图像提供了一组稀疏的人类相对反射判断，作为内在图像的标准基准。许多方法使用IIW来学习图像与其反射层之间的统计相关性。尽管学习在高性能方面扮演着重要的角色，但我们表明，标准的信号处理技术可以达到与当前最新技术相媲美的性能。我们提出了密集反射预测CNN学习的损失函数。我们的结果表明，一个简单的像素决策，没有任何背景或事先的知识，足以提供一个强大的IIW基线。这设定了只有两个其他方法超越的竞争基准。然后，我们开发了一个联合双边滤波方法，实现强大的反射率恒定的先验知识。这种过滤操作可以应用于任何固有的图像算法，我们改进了以前的几个结果，实现了IIW上的最新技术。我们的研究结果表明，迄今为止，基于学习的方法的效果可能被高估了。明确的先验知识对于在固有图像分解中获得高性能至少同等重要。

##### URL
[https://arxiv.org/abs/1612.05062](https://arxiv.org/abs/1612.05062)

##### PDF
[https://arxiv.org/pdf/1612.05062](https://arxiv.org/pdf/1612.05062)

