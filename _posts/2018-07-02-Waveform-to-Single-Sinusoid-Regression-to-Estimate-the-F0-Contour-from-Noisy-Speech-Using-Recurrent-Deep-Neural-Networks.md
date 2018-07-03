---
layout: post
title: "Waveform to Single Sinusoid Regression to Estimate the F0 Contour from Noisy Speech Using Recurrent Deep Neural Networks"
date: 2018-07-02 15:42:00
categories: arXiv_CL
tags: arXiv_CL Tracking RNN Classification
author: Akihiro Kato, Tomi Kinnunen
mathjax: true
---

* content
{:toc}

##### Abstract
The fundamental frequency (F0) represents pitch in speech that determines prosodic characteristics of speech and is needed in various tasks for speech analysis and synthesis. Despite decades of research on this topic, F0 estimation at low signal-to-noise ratios (SNRs) in unexpected noise conditions remains difficult. This work proposes a new approach to noise robust F0 estimation using a recurrent neural network (RNN) trained in a supervised manner. Recent studies employ deep neural networks (DNNs) for F0 tracking as a frame-by-frame classification task into quantised frequency states but we propose waveform-to-sinusoid regression instead to achieve both noise robustness and accurate estimation with increased frequency resolution. 
 Experimental results with PTDB-TUG corpus contaminated by additive noise (NOISEX-92) demonstrate that the proposed method improves gross pitch error (GPE) rate and fine pitch error (FPE) by more than 35 % at SNRs between -10 dB and +10 dB compared with well-known noise robust F0 tracker, PEFAC. Furthermore, the proposed method also outperforms state-of-the-art DNN-based approaches by more than 15 % in terms of both FPE and GPE rate over the preceding SNR range.

##### Abstract (translated by Google)
基频（F0）表示语音中的音调，其确定语音的韵律特征并且在语音分析和合成的各种任务中是需要的。尽管对该主题进行了数十年的研究，但在意外噪声条件下的低信噪比（SNR）下的F0估计仍然很困难。这项工作提出了一种使用以监督方式训练的递归神经网络（RNN）进行噪声鲁棒F0估计的新方法。最近的研究采用深度神经网络（DNN）将F0跟踪作为逐帧分类任务进入量化频率状态，但我们提出波形到正弦波回归，而不是通过提高频率分辨率来实现噪声鲁棒性和准确估计。
 PTDB-TUG语料库受加性噪声污染的实验结果（NOISEX-92）表明，该方法在-10 dB和+10之间的SNR下将总节距误差（GPE）率和精细间距误差（FPE）提高了35％以上dB与众所周知的噪声稳健F0跟踪器PEFAC相比较。此外，就先前SNR范围内的FPE和GPE速率而言，所提出的方法也优于基于DNN的现有方法超过15％。

##### URL
[http://arxiv.org/abs/1807.00752](http://arxiv.org/abs/1807.00752)

##### PDF
[http://arxiv.org/pdf/1807.00752](http://arxiv.org/pdf/1807.00752)

