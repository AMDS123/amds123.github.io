---
layout: post
title: "Boosting Noise Robustness of Acoustic Model via Deep Adversarial Training"
date: 2018-05-02 06:06:24
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN Speech_Recognition Optimization Recognition
author: Bin Liu, Shuai Nie, Yaping Zhang, Dengfeng Ke, Shan Liang, Wenju Liu1
mathjax: true
---

* content
{:toc}

##### Abstract
In realistic environments, speech is usually interfered by various noise and reverberation, which dramatically degrades the performance of automatic speech recognition (ASR) systems. To alleviate this issue, the commonest way is to use a well-designed speech enhancement approach as the front-end of ASR. However, more complex pipelines, more computations and even higher hardware costs (microphone array) are additionally consumed for this kind of methods. In addition, speech enhancement would result in speech distortions and mismatches to training. In this paper, we propose an adversarial training method to directly boost noise robustness of acoustic model. Specifically, a jointly compositional scheme of generative adversarial net (GAN) and neural network-based acoustic model (AM) is used in the training phase. GAN is used to generate clean feature representations from noisy features by the guidance of a discriminator that tries to distinguish between the true clean signals and generated signals. The joint optimization of generator, discriminator and AM concentrates the strengths of both GAN and AM for speech recognition. Systematic experiments on CHiME-4 show that the proposed method significantly improves the noise robustness of AM and achieves the average relative error rate reduction of 23.38% and 11.54% on the development and test set, respectively.

##### Abstract (translated by Google)
在现实环境中，语音通​​常会受到各种噪声和混响的干扰，从而大大降低了自动语音识别（ASR）系统的性能。为了缓解这个问题，最常见的方式是使用精心设计的语音增强方法作为ASR的前端。然而，对于这种方法，额外消耗更复杂的流水线，更多的计算和更高的硬件成本（麦克风阵列）。另外，语音增强会导致语音失真和训练不匹配。在本文中，我们提出了一种直接增强声学模型噪声鲁棒性的对抗训练方法。具体来说，在训练阶段使用生成对抗网（GAN）和基于神经网络的声学模型（AM）的联合组合方案。 GAN用于通过鉴别器的引导产生来自噪声特征的干净特征表示，所述鉴别器试图区分真正的干净信号和所产生的信号。发生器，鉴频器和AM的联合优化集中了GAN和AM两者对语音识别的优势。对CHiME-4进行的系统实验表明，该方法显着提高了AM的噪声鲁棒性，在开发和测试集上平均相对误差率分别降低23.38％和11.54％。

##### URL
[http://arxiv.org/abs/1805.01357](http://arxiv.org/abs/1805.01357)

##### PDF
[http://arxiv.org/pdf/1805.01357](http://arxiv.org/pdf/1805.01357)

