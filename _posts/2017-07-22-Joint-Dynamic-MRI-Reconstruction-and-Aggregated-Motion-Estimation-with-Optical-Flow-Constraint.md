---
layout: post
title: "Joint Dynamic MRI Reconstruction and Aggregated Motion Estimation with Optical Flow Constraint"
date: 2017-07-22 02:23:21
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding Optimization
author: Ningning Zhao, Daniel O'Connor, Dan Ruan, Adrian Basarab, Peng Hu, Ke Sheng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework to jointly reconstruct the dynamic magnetic resonance images (DMRI) and estimate the motion vectors from the under-sampled measurements. Due to the inherent motion effects in DMRI acquisition, reconstruction of DMRI using motion estimation/compensation has been studied under a compressed sensing (CS) scheme. In this paper, by embedding the intensity based optical flow (OF) constraint into the traditional CS scheme, we are able to couple the DMRI reconstruction with vector motion estimation. The resulting optimization problem is then solved by a primal-dual algorithm with linesearch due to its efficiency when dealing with non-differentiable problems. Moreover, the proposed framework is capable of handling a wide class of prior information (regularizations) for DMRI reconstruction, such as sparsity, low rank, total variation. In order to reduce the computational cost, the OF constraint is employed in a specific coarse scale. Experiments on various DMRI data, ranging from in vivo lung data to simulated phantom, validate the reconstruction quality improvement using the proposed scheme in comparison to several state-of-the-art algorithms.

##### Abstract (translated by Google)
本文提出了一个新的框架，联合重建动态磁共振图像（DMRI）和估计从欠采样测量运动矢量。由于DMRI采集中固有的运动效应，已经在压缩感测（CS）方案下研究了使用运动估计/补偿的DMRI重建。在本文中，通过将基于强度的光流（OF）约束嵌入到传统的CS方案中，我们能够将DMRI重建与向量运动估计耦合。由此产生的优化问题由于其在处理不可区分问题时的效率，因此通过使用原子对的算法来解决。此外，所提出的框架能够处理用于DMRI重建的大量先验信息（正则化），例如稀疏性，低秩，总变差。为了降低计算成本，OF约束被用于特定的粗尺度。对各种DMRI数据进行的实验，从体内肺部数据到模拟体模，使用所提出的方案与几种最先进的算法进行比较，验证了重建质量的改善。

##### URL
[https://arxiv.org/abs/1707.07089](https://arxiv.org/abs/1707.07089)

##### PDF
[https://arxiv.org/pdf/1707.07089](https://arxiv.org/pdf/1707.07089)

