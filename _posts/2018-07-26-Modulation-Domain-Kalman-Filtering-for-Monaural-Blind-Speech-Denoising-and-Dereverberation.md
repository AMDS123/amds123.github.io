---
layout: post
title: "Modulation-Domain Kalman Filtering for Monaural Blind Speech Denoising and Dereverberation"
date: 2018-07-26 16:40:12
categories: arXiv_SD
tags: arXiv_SD Relation
author: Nikolaos Dionelis, Mike Brookes
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a monaural speech enhancement algorithm based on modulation-domain Kalman filtering to blindly track the time-frequency log-magnitude spectra of speech and reverberation. We propose an adaptive algorithm that performs blind joint denoising and dereverberation, while accounting for the inter-frame speech dynamics, by estimating the posterior distribution of the speech log-magnitude spectrum given the log-magnitude spectrum of the noisy reverberant speech. The Kalman filter update step models the non-linear relations between the speech, noise and reverberation log-spectra. The Kalman filtering algorithm uses a signal model that takes into account the reverberation parameters of the reverberation time, $T_{60}$, and the direct-to-reverberant energy ratio (DRR) and also estimates and tracks the $T_{60}$ and the DRR in every frequency bin in order to improve the estimation of the speech log-magnitude spectrum. The Kalman filtering algorithm is tested and graphs that depict the estimated reverberation features over time are examined. The proposed algorithm is evaluated in terms of speech quality, speech intelligibility and dereverberation performance for a range of reverberation parameters and SNRs, in different noise types, and is also compared to competing denoising and dereverberation techniques. Experimental results using noisy reverberant speech demonstrate the effectiveness of the enhancement algorithm.

##### Abstract (translated by Google)
我们描述了一种基于调制域卡尔曼滤波的单声道语音增强算法，以盲目地跟踪语音和混响的时频对数幅度谱。我们提出了一种自适应算法，通过在给定嘈杂混响语音的对数幅度谱的情况下估计语音对数幅度谱的后验分布来执行盲联合去噪和去混响，同时考虑帧间语音动态。卡尔曼滤波器更新步骤模拟语音，噪声和混响对数谱之间的非线性关系。卡尔曼滤波算法使用信号模型，该模型考虑混响时间的混响参数$ T_ {60} $和直接混响能量比（DRR），并估计和跟踪$ T_ {60} $和每个频率仓中的DRR，以便改进语音对数幅度谱的估计。测试了卡尔曼滤波算法，并且检查了描绘估计的混响特征随时间的曲线图。所提出的算法在语音质量，语音清晰度和去混响性能方面针对不同噪声类型的一系列混响参数和SNR进行评估，并且还与竞争去噪和去混响技术进行比较。使用嘈杂的混响语音的实验结果证明了增强算法的有效性。

##### URL
[http://arxiv.org/abs/1807.10236](http://arxiv.org/abs/1807.10236)

##### PDF
[http://arxiv.org/pdf/1807.10236](http://arxiv.org/pdf/1807.10236)

