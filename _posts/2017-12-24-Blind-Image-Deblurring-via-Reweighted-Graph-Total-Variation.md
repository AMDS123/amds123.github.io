---
layout: post
title: "Blind Image Deblurring via Reweighted Graph Total Variation"
date: 2017-12-24 05:01:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization
author: Yuanchao Bai, Gene Cheung, Xianming Liu, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Blind image deblurring, i.e., deblurring without knowledge of the blur kernel, is a highly ill-posed problem. The problem can be solved in two parts: i) estimate a blur kernel from the blurry image, and ii) given estimated blur kernel, de-convolve blurry input to restore the target image. In this paper, by interpreting an image patch as a signal on a weighted graph, we first argue that a skeleton image---a proxy that retains the strong gradients of the target but smooths out the details---can be used to accurately estimate the blur kernel and has a unique bi-modal edge weight distribution. We then design a reweighted graph total variation (RGTV) prior that can efficiently promote bi-modal edge weight distribution given a blurry patch. However, minimizing a blind image deblurring objective with RGTV results in a non-convex non-differentiable optimization problem. We propose a fast algorithm that solves for the skeleton image and the blur kernel alternately. Finally with the computed blur kernel, recent non-blind image deblurring algorithms can be applied to restore the target image. Experimental results show that our algorithm can robustly estimate the blur kernel with large kernel size, and the reconstructed sharp image is competitive against the state-of-the-art methods.

##### Abstract (translated by Google)
盲图像去模糊（deblurring），即在不知道模糊核的情况下进行去模糊，是一个非常不适合的问题。该问题可以分为两部分来解决：1）从模糊图像中估计模糊核，2）给出估计的模糊核，将模糊输入解卷积以恢复目标图像。在本文中，通过将图像块作为加权图上的信号进行解释，我们首先争辩说，一个骨架图像---保留目标的强梯度但平滑细节的代理 - 可用于准确地估计模糊核并具有独特的双模式边缘权重分布。然后，我们设计一个重加权图总变异（RGTV），在给定一个模糊补丁的情况下，可以有效地促进双峰的边缘重量分布。然而，用RGTV最小化盲目去模糊目标会导致非凸非可微优化问题。我们提出了一个快速算法，交替地解决了骨架图像和模糊核。最后利用计算出的模糊内核，可以应用最近的非盲图像去模糊算法来恢复目标图像。实验结果表明，该算法能够鲁棒地估计出大核大小的模糊核，重构出来的清晰图像与现有技术相比具有竞争优势。

##### URL
[http://arxiv.org/abs/1712.08877](http://arxiv.org/abs/1712.08877)

##### PDF
[http://arxiv.org/pdf/1712.08877](http://arxiv.org/pdf/1712.08877)

