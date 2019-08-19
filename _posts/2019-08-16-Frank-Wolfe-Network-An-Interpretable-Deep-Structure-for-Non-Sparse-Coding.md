---
layout: post
title: "Frank-Wolfe Network: An Interpretable Deep Structure for Non-Sparse Coding"
date: 2019-08-16 01:28:00
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse CNN Gradient_Descent Recognition
author: Dong Liu, Ke Sun, Zhangyang Wang, Runsheng Liu, Zheng-Jun Zha
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of $L_p$-norm constrained coding is to convert signal into code that lies inside an $L_p$-ball and most faithfully reconstructs the signal. Previous works under the name of sparse coding considered the cases of $L_0$ and $L_1$ norms. The cases with $p&gt;1$ values, i.e. non-sparse coding studied in this paper, remain a difficulty. We propose an interpretable deep structure namely Frank-Wolfe Network (F-W Net), whose architecture is inspired by unrolling and truncating the Frank-Wolfe algorithm for solving an $L_p$-norm constrained problem with $p\geq 1$. We show that the Frank-Wolfe solver for the $L_p$-norm constraint leads to a novel closed-form nonlinear unit, which is parameterized by $p$ and termed $pool_p$. The $pool_p$ unit links the conventional pooling, activation, and normalization operations, making F-W Net distinct from existing deep networks either heuristically designed or converted from projected gradient descent algorithms. We further show that the hyper-parameter $p$ can be made learnable instead of pre-chosen in F-W Net, which gracefully solves the non-sparse coding problem even with unknown $p$. We evaluate the performance of F-W Net on an extensive range of simulations as well as the task of handwritten digit recognition, where F-W Net exhibits strong learning capability. We then propose a convolutional version of F-W Net, and apply the convolutional F-W Net into image denoising and super-resolution tasks, where F-W Net all demonstrates impressive effectiveness, flexibility, and robustness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.10252](http://arxiv.org/abs/1802.10252)

##### PDF
[http://arxiv.org/pdf/1802.10252](http://arxiv.org/pdf/1802.10252)

