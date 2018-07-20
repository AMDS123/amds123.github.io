---
layout: post
title: "Noise Adaptive Speech Enhancement using Domain Adversarial Training"
date: 2018-07-19 15:42:26
categories: arXiv_SD
tags: arXiv_SD Adversarial
author: Chien-Feng Liao, Yu Tsao, Hung-Yi Lee, Hsin-Min Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we propose a novel noise adaptive speech enhancement (SE) system, which employs a domain adversarial training (DAT) approach to tackle the issue of noise type mismatch between training and testing conditions. Such a mismatch is a critical problem in deep-learning-based SE systems. A large mismatch may cause serious performance degradation to the SE performance. Since we generally use a well trained SE system to handle various unseen noise types, the noise type mismatch commonly happens in real-world scenarios. The proposed noise adaptive SE system contains an encoder-decoder-based enhancement model and a domain discriminator model. During adaptation, the DAT approach encourages the encoder to produce noise invariant features based on the information from the discriminator model and consequentially increases the robustness of the enhancement model to unseen noise types. Here we regard stationary noises as the source domain (with ground-truth clean speech) and non-stationary noises as the target domain (without ground truth). We evaluated the proposed system on the TMHINT sentences. Experimental results show that the proposed noise adaptive SE system successfully provide notable PESQ (55.9%) and SSNR (26.1%) relative improvements over the SE system without performing noise adaptation.

##### Abstract (translated by Google)
在本研究中，我们提出了一种新颖的噪声自适应语音增强（SE）系统，该系统采用域对抗训练（DAT）方法来解决训练和测试条件之间噪声类型不匹配的问题。这种不匹配是基于深度学习的SE系统中的关键问题。大的不匹配可能导致SE性能严重降低。由于我们通常使用训练有素的SE系统来处理各种看不见的噪声类型，因此噪声类型不匹配通常发生在真实场景中。所提出的噪声自适应SE系统包含基于编码器 - 解码器的增强模型和域鉴别器模型。在自适应期间，DAT方法鼓励编码器基于来自鉴别器模型的信息产生噪声不变特征，并因此增强增强模型对不可见噪声类型的鲁棒性。在这里，我们将静止噪声视为源域（具有地面实况干净语音）和非静止噪声作为目标域（没有地面实况）。我们在TMHINT句子上评估了所提出的系统。实验结果表明，所提出的噪声自适应SE系统成功地提供了显着的PESQ（55.9％）和SSNR（26.1％）相对于SE系统的相对改进而没有执行噪声适应。

##### URL
[http://arxiv.org/abs/1807.07501](http://arxiv.org/abs/1807.07501)

##### PDF
[http://arxiv.org/pdf/1807.07501](http://arxiv.org/pdf/1807.07501)

