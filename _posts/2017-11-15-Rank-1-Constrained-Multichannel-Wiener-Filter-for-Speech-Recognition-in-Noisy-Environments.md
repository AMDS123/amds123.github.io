---
layout: post
title: "Rank-1 Constrained Multichannel Wiener Filter for Speech Recognition in Noisy Environments"
date: 2017-11-15 03:26:31
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Ziteng Wang, Emmanuel Vincent, Romain Serizel, Yonghong Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Multichannel linear filters, such as the Multichannel Wiener Filter (MWF) and the Generalized Eigenvalue (GEV) beamformer are popular signal processing techniques which can improve speech recognition performance. In this paper, we present an experimental study on these linear filters in a specific speech recognition task, namely the CHiME-4 challenge, which features real recordings in multiple noisy environments. Specifically, the rank-1 MWF is employed for noise reduction and a new constant residual noise power constraint is derived which enhances the recognition performance. To fulfill the underlying rank-1 assumption, the speech covariance matrix is reconstructed based on eigenvectors or generalized eigenvectors. Then the rank-1 constrained MWF is evaluated with alternative multichannel linear filters under the same framework, which involves a Bidirectional Long Short-Term Memory (BLSTM) network for mask estimation. The proposed filter outperforms alternative ones, leading to a 40% relative Word Error Rate (WER) reduction compared with the baseline Weighted Delay and Sum (WDAS) beamformer on the real test set, and a 15% relative WER reduction compared with the GEV-BAN method. The results also suggest that the speech recognition accuracy correlates more with the Mel-frequency cepstral coefficients (MFCC) feature variance than with the noise reduction or the speech distortion level.

##### Abstract (translated by Google)
多通道线性滤波器，如多通道维纳滤波器（MWF）和广义特征值（GEV）波束形成器是流行的信号处理技术，可以提高语音识别性能。在本文中，我们提出了一个关于这些线性滤波器在特定语音识别任务中的实验研究，即CHiME-4挑战，它在多个噪声环境中具有真实记录。具体而言，采用秩为1的MWF进行降噪，导出新的恒定残差噪声功率约束，提高了识别性能。为了完成潜在的秩-1假设，基于特征向量或广义特征向量来重建语音协方差矩阵。然后，在相同的框架下，使用替代的多通道线性滤波器评估秩为1的约束MWF，其涉及用于掩模估计的双向长期短期存储器（BLSTM）网络。所提出的滤波器优于其他选择，与真实测试集上的基线加权延迟和和（WDAS）波束成形器相比，导致40％的相对误码率（WER）降低，相对于GEV- BAN方法。结果还表明，与噪声减少或话语失真水平相比，语音识别精度与Mel频率倒谱系数（MFCC）特征方差更相关。

##### URL
[https://arxiv.org/abs/1707.00201](https://arxiv.org/abs/1707.00201)

##### PDF
[https://arxiv.org/pdf/1707.00201](https://arxiv.org/pdf/1707.00201)

