---
layout: post
title: "Graph-Based Blind Image Deblurring From a Single Photograph"
date: 2018-02-22 07:48:18
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Quantitative
author: Yuanchao Bai, Gene Cheung, Xianming Liu, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Blind image deblurring, i.e., deblurring without knowledge of the blur kernel, is a highly ill-posed problem. The problem can be solved in two parts: i) estimate a blur kernel from the blurry image, and ii) given estimated blur kernel, de-convolve blurry input to restore the target image. In this paper, we propose a graph-based blind image deblurring algorithm by interpreting an image patch as a signal on a weighted graph. Specifically, we first argue that a skeleton image---a proxy that retains the strong gradients of the target but smooths out the details---can be used to accurately estimate the blur kernel and has a unique bi-modal edge weight distribution. Then, we design a reweighted graph total variation (RGTV) prior that can efficiently promote a bi-modal edge weight distribution given a blurry patch. Further, to analyze RGTV in the graph frequency domain, we introduce a new weight function to represent RGTV as a graph $l_1$-Laplacian regularizer. This leads to a graph spectral filtering interpretation of the prior with desirable properties, including robustness to noise and blur, strong piecewise smooth (PWS) filtering and sharpness promotion. Minimizing a blind image deblurring objective with RGTV results in a non-convex non-differentiable optimization problem. We leverage the new graph spectral interpretation for RGTV to design an efficient algorithm that solves for the skeleton image and the blur kernel alternately. Specifically for Gaussian blur, we propose a further speedup strategy for blind Gaussian deblurring using accelerated graph spectral filtering. Finally, with the computed blur kernel, recent non-blind image deblurring algorithms can be applied to restore the target image. Experimental results demonstrate that our algorithm successfully restores latent sharp images and outperforms state-of-the-art methods quantitatively and qualitatively.

##### Abstract (translated by Google)
盲图像去模糊，即在不知道模糊核心的情况下去模糊，是一个非常不适合的问题。该问题可以分两部分来解决：i）从模糊图像中估计模糊核，ii）给出估计的模糊核，将模糊输入解卷积以恢复目标图像。在本文中，我们提出了一种基于图的盲图像去模糊算法，将图像块解释为加权图上的信号。具体来说，我们首先论证一个骨架图像---保留目标的强梯度但平滑细节的代理 - 可用于精确估计模糊核并具有独特的双模态边权分布。然后，我们设计一个重加权图总变异（RGTV），然后在给定模糊补丁的情况下可以有效地促进双模式边缘权重分布。此外，为了分析图频域中的RGTV，我们引入一个新的权重函数来将RGTV表示为一个图$ l_1 $ -Laplacian正则化器。这导致图形光谱过滤解释先前具有期望特性，包括对噪声和模糊的鲁棒性，强分段平滑（PWS）滤波和锐度提升。用RGTV最小化盲目去模糊目标会导致非凸非可微优化问题。我们利用RGTV的新图谱解释来设计一个高效算法，交替地解决骨架图像和模糊核问题。特别是对于高斯模糊，我们提出了进一步的加速策略，用于使用加速图谱滤波的盲高斯去模糊。最后，利用计算出的模糊内核，可以应用最近的非盲图像去模糊算法来恢复目标图像。实验结果表明，我们的算法成功恢复了潜在的清晰图像，并且在数量和质量上均优于最先进的方法。

##### URL
[http://arxiv.org/abs/1802.07929](http://arxiv.org/abs/1802.07929)

##### PDF
[http://arxiv.org/pdf/1802.07929](http://arxiv.org/pdf/1802.07929)

