---
layout: post
title: "Speaker Recognition from Raw Waveform with SincNet"
date: 2018-09-09 19:19:14
categories: arXiv_SD
tags: arXiv_SD CNN Deep_Learning Recognition
author: Mirco Ravanelli, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning is progressively gaining popularity as a viable alternative to i-vectors for speaker recognition. Promising results have been recently obtained with Convolutional Neural Networks (CNNs) when fed by raw speech samples directly. Rather than employing standard hand-crafted features, the latter CNNs learn low-level speech representations from waveforms, potentially allowing the network to better capture important narrow-band speaker characteristics such as pitch and formants. Proper design of the neural network is crucial to achieve this goal. This paper proposes a novel CNN architecture, called SincNet, that encourages the first convolutional layer to discover more meaningful filters. SincNet is based on parametrized sinc functions, which implement band-pass filters. In contrast to standard CNNs, that learn all elements of each filter, only low and high cutoff frequencies are directly learned from data with the proposed method. This offers a very compact and efficient way to derive a customized filter bank specifically tuned for the desired application. Our experiments, conducted on both speaker identification and speaker verification tasks, show that the proposed architecture converges faster and performs better than a standard CNN on raw waveforms.

##### Abstract (translated by Google)
深度学习作为说话人识别的i向量的可行替代方案逐渐普及。最近通过直接由原始语音样本馈送的卷积神经网络（CNN）获得了有希望的结果。后者CNN不是采用标准的手工制作功能，而是从波形中学习低级语音表示，可能使网络更好地捕捉重要的窄带扬声器特性，例如音高和共振峰。正确设计神经网络对于实现这一目标至关重要。本文提出了一种新的CNN架构，称为SincNet，它鼓励第一个卷积层发现更有意义的滤波器。 SincNet基于参数化sinc函数，它实现了带通滤波器。与标准CNN相比，学习每个滤波器的所有元素，仅使用所提出的方法从数据中直接学习低和高截止频率。这提供了一种非常紧凑和有效的方法来获得专门针对所需应用进行调整的定制滤波器组。我们在扬声器识别和扬声器验证任务上进行的实验表明，所提出的架构在原始波形上收敛速度更快，性能优于标准CNN。

##### URL
[http://arxiv.org/abs/1808.00158](http://arxiv.org/abs/1808.00158)

##### PDF
[http://arxiv.org/pdf/1808.00158](http://arxiv.org/pdf/1808.00158)

