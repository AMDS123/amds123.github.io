---
layout: post
title: "Motion Compensated Dynamic MRI Reconstruction with Local Affine Optical Flow Estimation"
date: 2018-02-19 03:16:18
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding Optimization
author: Ningning Zhao, Daniel O&#x27;Connor, Adrian Basarab, Dan Ruan, Peng Hu, Ke Sheng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework to reconstruct the dynamic magnetic resonance images (DMRI) with motion compensation (MC). Due to the inherent motion effects during DMRI acquisition, reconstruction of DMRI using motion estimation/compensation (ME/MC) has been studied under a compressed sensing (CS) scheme. In this paper, by embedding the intensity-based optical flow (OF) constraint into the traditional CS scheme, we are able to couple the DMRI reconstruction with motion field estimation. The formulated optimization problem is solved by a primal-dual algorithm with linesearch due to its efficiency when dealing with non-differentiable problems. With the estimated motion field, the DMRI reconstruction is refined through MC. By employing the multi-scale coarse-to-fine strategy, we are able to update the variables(temporal image sequences and motion vectors) and to refine the image reconstruction alternately. Moreover, the proposed framework is capable of handling a wide class of prior information (regularizations) for DMRI reconstruction, such as sparsity, low rank and total variation. Experiments on various DMRI data, ranging from in vivo lung to cardiac dataset, validate the reconstruction quality improvement using the proposed scheme in comparison to several state-of-the-art algorithms.

##### Abstract (translated by Google)
本文提出了一种新的框架来重建具有运动补偿（MC）的动态磁共振图像（DMRI）。由于在DMRI采集期间固有的运动效应，已经在压缩感测（CS）方案下研究了使用运动估计/补偿（ME / MC）重建DMRI。在本文中，通过将基于强度的光流（OF）约束嵌入到传统的CS方案中，我们能够将DMRI重建与运动场估计结合起来。由于处理不可微分问题时的效率，因此用公式表示的原始 - 对偶算法解决了公式化的优化问题。利用估计的运动场，通过MC改进DMRI重建。通过采用多尺度的从粗到精的策略，我们能够更新变量（时间图像序列和运动矢量）并交替地优化图像重建。此外，所提出的框架能够处理用于DMRI重建的大量先验信息（正则化），例如稀疏性，低秩和总变差。对各种DMRI数据进行实验，从体内肺到心脏数据集，使用所提出的方案验证重建质量改进，并与几种最先进的算法进行比较。

##### URL
[http://arxiv.org/abs/1707.07089](http://arxiv.org/abs/1707.07089)

##### PDF
[http://arxiv.org/pdf/1707.07089](http://arxiv.org/pdf/1707.07089)

