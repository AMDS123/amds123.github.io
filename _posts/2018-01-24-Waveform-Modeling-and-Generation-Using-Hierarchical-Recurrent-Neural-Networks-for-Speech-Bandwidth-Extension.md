---
layout: post
title: "Waveform Modeling and Generation Using Hierarchical Recurrent Neural Networks for Speech Bandwidth Extension"
date: 2018-01-24 08:53:55
categories: arXiv_SD
tags: arXiv_SD CNN RNN
author: Zhen-Hua Ling, Yang Ai, Yu Gu, Li-Rong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a waveform modeling and generation method using hierarchical recurrent neural networks (HRNN) for speech bandwidth extension (BWE). Different from conventional BWE methods which predict spectral parameters for reconstructing wideband speech waveforms, this BWE method models and predicts waveform samples directly without using vocoders. Inspired by SampleRNN which is an unconditional neural audio generator, the HRNN model represents the distribution of each wideband or high-frequency waveform sample conditioned on the input narrowband waveform samples using a neural network composed of long short-term memory (LSTM) layers and feed-forward (FF) layers. The LSTM layers form a hierarchical structure and each layer operates at a specific temporal resolution to efficiently capture long-span dependencies between temporal sequences. Furthermore, additional conditions, such as the bottleneck (BN) features derived from narrowband speech using a deep neural network (DNN)-based state classifier, are employed as auxiliary input to further improve the quality of generated wideband speech. The experimental results of comparing several waveform modeling methods show that the HRNN-based method can achieve better speech quality and run-time efficiency than the dilated convolutional neural network (DCNN)-based method and the plain sample-level recurrent neural network (SRNN)-based method. Our proposed method also outperforms the conventional vocoder-based BWE method using LSTM-RNNs in terms of the subjective quality of the reconstructed wideband speech.

##### Abstract (translated by Google)
本文提出了一种使用递阶递归神经网络（HRNN）进行语音带宽扩展（BWE）的波形建模和生成方法。与传统的用于重构宽带语音波形的预测频谱参数的BWE方法不同，该BWE方法直接建模并预测波形样本，而不使用声码器。受到作为无条件神经音频发生器的SampleRNN的启发，HRNN模型使用由长期短期记忆（LSTM）层和馈送组成的神经网络来表示在输入窄带波形样本上调节的每个宽带或高频波形样本的分布前向（FF）层。 LSTM层形成一个层次结构，每层以特定的时间分辨率运行，以有效捕获时间序列之间的长期依赖关系。此外，使用基于深度神经网络（DNN）的状态分类器从窄带语音中得到的瓶颈（BN）特征等附加条件作为辅助输入，以进一步提高生成的宽带语音的质量。比较几种波形建模方法的实验结果表明，基于HRNN的方法比基于膨胀卷积神经网络（DCNN）的方法和简单样本级递归神经网络（SRNN）具有更好的语音质量和运行时效率，基于方法。我们提出的方法在重构宽带语音的主观质量方面也优于传统的基于声码器的基于LSTM-RNN的BWE方法。

##### URL
[http://arxiv.org/abs/1801.07910](http://arxiv.org/abs/1801.07910)

##### PDF
[http://arxiv.org/pdf/1801.07910](http://arxiv.org/pdf/1801.07910)

