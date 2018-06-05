---
layout: post
title: "k-Space Deep Learning for Parallel MRI: Application to Time-Resolved MR Angiography"
date: 2018-06-03 14:56:46
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Eunju Cha, Eung Yeop Kim, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Time-resolved angiography with interleaved stochastic trajectories (TWIST) has been widely used for dynamic contrast enhanced MRI (DCE-MRI). To achieve highly accelerated acquisitions, TWIST combines the periphery of the k-space data from several adjacent frames to reconstruct one temporal frame. However, this view-sharing scheme limits the true temporal resolution of TWIST. In addition, since the k-space sampling patterns have been specially designed for a specific generalized autocalibrating partial parallel acquisition (GRAPPA) factor, it is not possible to reduce the number of views in order to reconstruct images with a better temporal resolution. To address these issues, this paper proposes a novel k-space deep learning approach for parallel MRI. In particular, inspired by the recent mathematical discovery that links Hankel matrix decomposition to deep learning, we have implemented our neural network so that accurate k-space interpolations are performed simultaneously for multiple coils by exploiting the redundancies along the coils and images. In addition, the proposed method can immediately generate reconstruction results with different numbers of view-sharing, allowing us to exploit the trade-off between spatial and temporal resolution. Reconstruction results using in vivo TWIST data set confirm the accuracy and the flexibility of the proposed method.

##### Abstract (translated by Google)
具有交错随机轨迹（TWIST）的时间分辨血管造影术已广泛用于动态对比增强MRI（DCE-MRI）。为了实现高度加速的采集，TWIST结合来自几个相邻帧的k空间数据的外围以重建一个时间帧。然而，这种观点共享方案限制了TWIST的真实时间分辨率。另外，由于k空间采样模式是专门为特定的广义自动校准部分并行采集（GRAPPA）因子设计的，因此不可能减少视图的数量以重建时间分辨率更好的图像。为了解决这些问题，本文提出了一种新的并行MRI的k空间深度学习方法。特别是，最近的数学发现将Hankel矩阵分解与深度学习联系起来，我们实现了我们的神经网络，通过利用沿线圈和图像的冗余，对多个线圈同时执行精确的k空间插值。此外，所提出的方法可以立即生成具有不同数量视图共享的重建结果，使我们能够利用空间和时间分辨率之间的权衡。使用体内TWIST数据集的重建结果证实了所提出方法的准确性和灵活性。

##### URL
[http://arxiv.org/abs/1806.00806](http://arxiv.org/abs/1806.00806)

##### PDF
[http://arxiv.org/pdf/1806.00806](http://arxiv.org/pdf/1806.00806)

