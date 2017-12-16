---
layout: post
title: "Comparison of Time-Frequency Representations for Environmental Sound Classification using Convolutional Neural Networks"
date: 2017-06-22 03:23:09
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition CNN Classification Recognition
author: M. Huzaifah
mathjax: true
---

* content
{:toc}

##### Abstract
Recent successful applications of convolutional neural networks (CNNs) to audio classification and speech recognition have motivated the search for better input representations for more efficient training. Visual displays of an audio signal, through various time-frequency representations such as spectrograms offer a rich representation of the temporal and spectral structure of the original signal. In this letter, we compare various popular signal processing methods to obtain this representation, such as short-time Fourier transform (STFT) with linear and Mel scales, constant-Q transform (CQT) and continuous Wavelet transform (CWT), and assess their impact on the classification performance of two environmental sound datasets using CNNs. This study supports the hypothesis that time-frequency representations are valuable in learning useful features for sound classification. Moreover, the actual transformation used is shown to impact the classification accuracy, with Mel-scaled STFT outperforming the other discussed methods slightly and baseline MFCC features to a large degree. Additionally, we observe that the optimal window size during transformation is dependent on the characteristics of the audio signal and architecturally, 2D convolution yielded better results in most cases compared to 1D.

##### Abstract (translated by Google)
卷积神经网络（CNNs）最近在音频分类和语音识别方面的成功应用促使人们寻求更好的输入表示以进行更有效的训练。音频信号的视觉显示，通过诸如频谱图的各种时间频率表示提供了原始信号的时间和频谱结构的丰富表示。在这封信中，我们比较了各种流行的信号处理方法，以获得这种表示，如线性和梅尔尺度的短时傅里叶变换（STFT），恒定Q变换（CQT）和连续小波变换（CWT），并评估它们对使用CNN的两个环境声音数据集的分类性能的影响。这项研究支持这样的假设，时频表示在学习有用的声音分类特征方面是有价值的。此外，所使用的实际转换被显示为影响分类准确度，Mel比例STFT比其他讨论的方法稍微优于其他方法，并且基线MFCC具有很大程度的特征。另外，我们观察到转换期间的最佳窗口大小取决于音频信号的特性，并且在架构上，与1D相比，在大多数情况下二维卷积产生更好的结果。

##### URL
[https://arxiv.org/abs/1706.07156](https://arxiv.org/abs/1706.07156)

##### PDF
[https://arxiv.org/pdf/1706.07156](https://arxiv.org/pdf/1706.07156)

