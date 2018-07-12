---
layout: post
title: "Temporal Convolution Networks for Real-Time Abdominal Fetal Aorta Analysis with Ultrasound"
date: 2018-07-11 10:22:38
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Nicolo&#x27; Savioli, Silvia Visentin, Erich Cosmi, Enrico Grisan, Pablo Lamata, Giovanni Montana
mathjax: true
---

* content
{:toc}

##### Abstract
The automatic analysis of ultrasound sequences can substantially improve the efficiency of clinical diagnosis. In this work we present our attempt to automate the challenging task of measuring the vascular diameter of the fetal abdominal aorta from ultrasound images. We propose a neural network architecture consisting of three blocks: a convolutional layer for the extraction of imaging features, a Convolution Gated Recurrent Unit (C-GRU) for enforcing the temporal coherence across video frames and exploiting the temporal redundancy of a signal, and a regularized loss function, called \textit{CyclicLoss}, to impose our prior knowledge about the periodicity of the observed signal. We present experimental evidence suggesting that the proposed architecture can reach an accuracy substantially superior to previously proposed methods, providing an average reduction of the mean squared error from $0.31 mm^2$ (state-of-art) to $0.09 mm^2$, and a relative error reduction from $8.1\%$ to $5.3\%$. The mean execution speed of the proposed approach of 289 frames per second makes it suitable for real time clinical use.

##### Abstract (translated by Google)
超声序列的自动分析可以显着提高临床诊断的效率。在这项工作中，我们提出了尝试自动化从超声图像测量胎儿腹主动脉血管直径的挑战性任务。我们提出了一个由三个块组成的神经网络架构：用于提取成像特征的卷积层，用于强制跨视频帧的时间相干性和利用信号的时间冗余的卷积门控递归单元（C-GRU），以及正则化损失函数，称为\ textit {CyclicLoss}，用于强加我们关于观测信号周期性的先验知识。我们提出的实验证据表明，所提出的架构可以达到远大于先前提出的方法的准确度，平均误差平均从0.31 mm ^ 2 $（现有技术）减少到$ 0.09 mm ^ 2 $，并且相对错误从$ 8.1 \％$减少到$ 5.3 \％$。所提出的方法的平均执行速度为每秒289帧，使其适合于实时临床使用。

##### URL
[http://arxiv.org/abs/1807.04056](http://arxiv.org/abs/1807.04056)

##### PDF
[http://arxiv.org/pdf/1807.04056](http://arxiv.org/pdf/1807.04056)

