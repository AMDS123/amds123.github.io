---
layout: post
title: "On the Importance of Super-Gaussian Speech Priors for Machine-Learning Based Speech Enhancement"
date: 2018-01-16 11:16:40
categories: arXiv_SD
tags: arXiv_SD Knowledge
author: Robert Rehr, Timo Gerkmann
mathjax: true
---

* content
{:toc}

##### Abstract
For enhancing noisy signals, machine-learning based single-channel speech enhancement schemes exploit prior knowledge about typical speech spectral structures. To ensure a good generalization and to meet requirements in terms of computational complexity and memory consumption, certain methods restrict themselves to learning speech spectral envelopes. We refer to these approaches as machine-learning spectral envelope (MLSE)-based approaches. 
 In this paper we show by means of theoretical and experimental analyses that for MLSE-based approaches, super-Gaussian priors allow for a reduction of noise between speech spectral harmonics which is not achievable using Gaussian estimators such as the Wiener filter. For the evaluation, we use a deep neural network (DNN)-based phoneme classifier and a low-rank nonnegative matrix factorization (NMF) framework as examples of MLSE-based approaches. A listening experiment and instrumental measures confirm that while super-Gaussian priors yield only moderate improvements for classic enhancement schemes, for MLSE-based approaches super-Gaussian priors clearly make an important difference and significantly outperform Gaussian priors.

##### Abstract (translated by Google)
为了增强噪声信号，基于机器学习的单通道语音增强方案利用关于典型语音频谱结构的先验知识。为了确保良好的泛化和满足计算复杂度和内存消耗方面的要求，某些方法限制自己学习语音频谱包络。我们将这些方法称为基于机器学习频谱包络（MLSE）的方法。
 在本文中，我们通过理论和实验分析来表明，对于基于MLSE的方法，超高斯先验允许使用高斯估计器（例如维纳滤波器）无法实现的语音频谱谐波之间的噪声降低。为了评估，我们使用基于深度神经网络（DNN）的音素分类器和低秩非负矩阵分解（NMF）框架作为基于MLSE的方法的示例。一个听力实验和仪器测量证实，虽然超高斯先验只对经典增强方案产生中等程度的改进，但对于基于MLSE的方法，超高斯先验显然具有重要的差异，并且明显优于高斯先验。

##### URL
[http://arxiv.org/abs/1703.05003](http://arxiv.org/abs/1703.05003)

##### PDF
[http://arxiv.org/pdf/1703.05003](http://arxiv.org/pdf/1703.05003)

