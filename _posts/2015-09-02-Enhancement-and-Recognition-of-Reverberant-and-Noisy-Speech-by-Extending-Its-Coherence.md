---
layout: post
title: "Enhancement and Recognition of Reverberant and Noisy Speech by Extending Its Coherence"
date: 2015-09-02 00:31:40
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Scott Wisdom, Thomas Powers, Les Atlas, James Pitton
mathjax: true
---

* content
{:toc}

##### Abstract
Most speech enhancement algorithms make use of the short-time Fourier transform (STFT), which is a simple and flexible time-frequency decomposition that estimates the short-time spectrum of a signal. However, the duration of short STFT frames are inherently limited by the nonstationarity of speech signals. The main contribution of this paper is a demonstration of speech enhancement and automatic speech recognition in the presence of reverberation and noise by extending the length of analysis windows. We accomplish this extension by performing enhancement in the short-time fan-chirp transform (STFChT) domain, an overcomplete time-frequency representation that is coherent with speech signals over longer analysis window durations than the STFT. This extended coherence is gained by using a linear model of fundamental frequency variation of voiced speech signals. Our approach centers around using a single-channel minimum mean-square error log-spectral amplitude (MMSE-LSA) estimator proposed by Habets, which scales coefficients in a time-frequency domain to suppress noise and reverberation. In the case of multiple microphones, we preprocess the data with either a minimum variance distortionless response (MVDR) beamformer, or a delay-and-sum beamformer (DSB). We evaluate our algorithm on both speech enhancement and recognition tasks for the REVERB challenge dataset. Compared to the same processing done in the STFT domain, our approach achieves significant improvement in terms of objective enhancement metrics (including PESQ---the ITU-T standard measurement for speech quality). In terms of automatic speech recognition (ASR) performance as measured by word error rate (WER), our experiments indicate that the STFT with a long window is more effective for ASR.

##### Abstract (translated by Google)
大多数语音增强算法利用短时傅里叶变换（STFT），这是一种简单而灵活的时频分解，可以估计信号的短时频谱。然而，短STFT帧的持续时间固有地受到语音信号的非平稳性的限制。本文的主要贡献是通过延长分析窗口的长度来演示混响和噪声情况下的语音增强和自动语音识别。我们通过在短时间扇出线性调频（STFChT）域中进行增强来实现这个扩展，STFChT域是一个与STFT相比在更长的分析窗持续时间内与语音信号相干的过完整时频表示。通过使用有声语音信号的基本频率变化的线性模型来获得这种扩展的一致性。我们的方法围绕使用由Habets提出的单通道最小均方误差对数谱振幅（MMSE-LSA）估计器来进行，该系统在时间 - 频率域中对系数进行缩放以抑制噪声和混响。在多个麦克风的情况下，我们用最小方差无失真响应（MVDR）波束形成器或延迟和求和波束形成器（DSB）来预处理数据。我们在REVERB挑战数据集的语音增强和识别任务上评估我们的算法。与在STFT域中完成的相同处理相比，我们的方法在客观增强度量（包括PESQ --- ITU-T语音质量标准测量）方面取得了显着的改进。在以字错误率（WER）测量的自动语音识别（ASR）性能方面，我们的实验表明，具有长窗的STFT对于ASR更有效。

##### URL
[https://arxiv.org/abs/1509.00533](https://arxiv.org/abs/1509.00533)

##### PDF
[https://arxiv.org/pdf/1509.00533](https://arxiv.org/pdf/1509.00533)

