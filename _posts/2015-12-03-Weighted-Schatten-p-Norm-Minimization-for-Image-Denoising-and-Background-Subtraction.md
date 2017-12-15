---
layout: post
title: "Weighted Schatten $p$-Norm Minimization for Image Denoising and Background Subtraction"
date: 2015-12-03 09:24:20
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Yuan Xie, Shuhang Gu, Yan Liu, Wangmeng Zuo, Wensheng Zhang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Low rank matrix approximation (LRMA), which aims to recover the underlying low rank matrix from its degraded observation, has a wide range of applications in computer vision. The latest LRMA methods resort to using the nuclear norm minimization (NNM) as a convex relaxation of the nonconvex rank minimization. However, NNM tends to over-shrink the rank components and treats the different rank components equally, limiting its flexibility in practical applications. We propose a more flexible model, namely the Weighted Schatten $p$-Norm Minimization (WSNM), to generalize the NNM to the Schatten $p$-norm minimization with weights assigned to different singular values. The proposed WSNM not only gives better approximation to the original low-rank assumption, but also considers the importance of different rank components. We analyze the solution of WSNM and prove that, under certain weights permutation, WSNM can be equivalently transformed into independent non-convex $l_p$-norm subproblems, whose global optimum can be efficiently solved by generalized iterated shrinkage algorithm. We apply WSNM to typical low-level vision problems, e.g., image denoising and background subtraction. Extensive experimental results show, both qualitatively and quantitatively, that the proposed WSNM can more effectively remove noise, and model complex and dynamic scenes compared with state-of-the-art methods.

##### Abstract (translated by Google)
低阶矩阵逼近（LRMA）是从退化观测中恢复潜在的低秩矩阵，在计算机视觉领域有着广泛的应用。最新的LRMA方法使用核范数最小化（NNM）作为非凸最小化的凸松弛。然而，NNM倾向于过分缩小等级组件，并且平等地处理不同等级的组件，限制了其在实际应用中的灵活性。我们提出了一个更灵活的模型，即加权Schatten $ p $ -Norm Minimization（WSNM），将NNM推广到Schatten $ p $ -norm最小化，并赋予不同奇异值的权值。所提出的WSNM不仅较好地逼近了原始的低秩假设，而且还考虑了不同秩元素的重要性。我们分析了WSNM的解，证明了在一定的权重置换下，WSNM可以等价地转化为独立的非凸$ l_p $ -norm子问题，其全局最优性可以通过广义迭代收缩算法得到有效解决。我们将WSNM应用于典型的低级视觉问题，例如图像去噪和背景减除。广泛的实验结果表明，在定性和定量两方面，所提出的WSNM能够更有效地去除噪声，并且与最先进的方法相比较来模拟复杂和动态的场景。

##### URL
[https://arxiv.org/abs/1512.01003](https://arxiv.org/abs/1512.01003)

##### PDF
[https://arxiv.org/pdf/1512.01003](https://arxiv.org/pdf/1512.01003)

