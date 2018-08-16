---
layout: post
title: "ACVAE-VC: Non-parallel many-to-many voice conversion with auxiliary classifier variational autoencoder"
date: 2018-08-13 23:31:01
categories: arXiv_SD
tags: arXiv_SD Regularization CNN
author: Hirokazu Kameoka, Takuhiro Kaneko, Kou Tanaka, Nobukatsu Hojo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a non-parallel many-to-many voice conversion (VC) method using a variant of the conditional variational autoencoder (VAE) called an auxiliary classifier VAE (ACVAE). The proposed method has three key features. First, it adopts fully convolutional architectures to devise the encoder and decoder networks so that the networks can learn conversion rules that capture time dependencies in the acoustic feature sequences of source and target speech. Second, it uses an information-theoretic regularization for the model training to ensure that the information in the attribute class label will not be lost in the conversion process. With regular CVAEs, the encoder and decoder are free to ignore the attribute class label input. This can be problematic since in such a situation, the attribute class label will have little effect on controlling the voice characteristics of input speech at test time. Such situations can be avoided by introducing an auxiliary classifier and training the encoder and decoder so that the attribute classes of the decoder outputs are correctly predicted by the classifier. Third, it avoids producing buzzy-sounding speech at test time by simply transplanting the spectral details of input speech into its converted version. Subjective evaluation experiments revealed that this simple method worked reasonably well on a non-parallel many-to-many speaker identity conversion task.

##### Abstract (translated by Google)
本文提出了一种非并行的多对多语音转换（VC）方法，该方法使用称为辅助分类器VAE（ACVAE）的条件变分自动编码器（VAE）的变体。该方法有三个关键特征。首先，它采用完全卷积体系结构来设计编码器和解码器网络，以便网络可以学习捕获源和​​目标语音的声学特征序列中的时间依赖性的转换规则。其次，它使用信息理论正则化进行模型训练，以确保属性类标签中的信息不会在转换过程中丢失。使用常规CVAE，编码器和解码器可以自由忽略属性类标签输入。这可能是有问题的，因为在这种情况下，属性类标签对于在测试时控制输入语音的语音特性几乎没有影响。通过引入辅助分类器并训练编码器和解码器可以避免这种情况，从而分类器正确地预测解码器输出的属性类。第三，它通过简单地将输入语音的频谱细节移植到其转换版本中，避免了在测试时产生嗡嗡声的语音。主观评估实验表明，这种简单的方法在非并行的多对多说话人身份转换任务上运行良好。

##### URL
[http://arxiv.org/abs/1808.05092](http://arxiv.org/abs/1808.05092)

##### PDF
[http://arxiv.org/pdf/1808.05092](http://arxiv.org/pdf/1808.05092)

