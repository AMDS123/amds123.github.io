---
layout: post
title: "Simple, Accurate, and Robust Nonparametric Blind Super-Resolution"
date: 2015-03-16 10:12:07
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Wen-Ze Shao, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a simple, accurate, and robust approach to single image nonparametric blind Super-Resolution (SR). This task is formulated as a functional to be minimized with respect to both an intermediate super-resolved image and a nonparametric blur-kernel. The proposed approach includes a convolution consistency constraint which uses a non-blind learning-based SR result to better guide the estimation process. Another key component is the unnatural bi-l0-l2-norm regularization imposed on the super-resolved, sharp image and the blur-kernel, which is shown to be quite beneficial for estimating the blur-kernel accurately. The numerical optimization is implemented by coupling the splitting augmented Lagrangian and the conjugate gradient (CG). Using the pre-estimated blur-kernel, we finally reconstruct the SR image by a very simple non-blind SR method that uses a natural image prior. The proposed approach is demonstrated to achieve better performance than the recent method by Michaeli and Irani [2] in both terms of the kernel estimation accuracy and image SR quality.

##### Abstract (translated by Google)
本文提出了一种简单，准确，稳健的单图像非参数盲超分辨率（SR）方法。这个任务被制定为一个功能，以最小化中间超分辨图像和非参数模糊核。所提出的方法包括卷积一致性约束，其使用基于非盲学习的SR结果来更好地指导估计过程。另一个关键部分是对超分辨锐图像和模糊核施加了非自然的双正则-l-l2范数正则化，这对于精确估计模糊核是非常有利的。数值优化是通过耦合分裂增广拉格朗日和共轭梯度（CG）来实现的。使用预估的模糊核，我们最终通过非常简单的使用自然图像的非盲SR方法重建SR图像。与Michaeli和Irani [2]最近提出的方法相比，所提出的方法在核估计精度和图像质量方面都有较好的表现。

##### URL
[https://arxiv.org/abs/1503.03187](https://arxiv.org/abs/1503.03187)

##### PDF
[https://arxiv.org/pdf/1503.03187](https://arxiv.org/pdf/1503.03187)

