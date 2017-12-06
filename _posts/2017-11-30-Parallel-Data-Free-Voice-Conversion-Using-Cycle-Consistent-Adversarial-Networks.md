---
layout: post
title: "Parallel-Data-Free Voice Conversion Using Cycle-Consistent Adversarial Networks"
date: 2017-11-30 09:57:19
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN CNN
author: Takuhiro Kaneko, Hirokazu Kameoka
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a parallel-data-free voice conversion (VC) method that can learn a mapping from source to target speech without relying on parallel data. The proposed method is general-purpose, high quality, and parallel-data-free, which works without any extra data, modules, or alignment procedure. It is also noteworthy that it avoids over-smoothing, which occurs in many conventional statistical model-based VC methods. Our method uses a cycle-consistent adversarial network (CycleGAN) with gated convolutional neural networks (CNNs) and an identity-mapping loss. The CycleGAN learns forward and inverse mappings simultaneously using adversarial and cycle-consistency losses. This makes it possible to find an optimal pseudo pair from unpaired data. Furthermore, the adversarial loss contributes to reducing over-smoothing of the converted feature sequence. We configure a CycleGAN with gated CNNs and train it with an identity-mapping loss. This allows the mapping function to capture sequential and hierarchical structures while preserving linguistic information. We evaluated our method on a parallel-data-free VC task. An objective evaluation showed that the converted feature sequence was near natural in terms of global variance and modulation spectra. A subjective evaluation showed that the quality of the converted speech was comparable to that obtained with the GMM-based method under advantageous conditions with parallel data.

##### Abstract (translated by Google)
我们提出了一种无需并行数据的语音转换（VC）方法，可以学习从源到目标语音的映射，而不依赖于并行数据。所提出的方法是通用的，高质量的，并行数据自由的，其不需要任何额外的数据，模块或对齐过程。值得注意的是，它避免了过度平滑，这在许多传统的基于统计模型的VC方法中发生。我们的方法使用具有门控卷积神经网络（CNN）的循环一致对抗网络（CycleGAN）和身份映射损失。 CycleGAN使用对抗和循环一致性损失同时学习前向和逆向映射。这使得从不成对的数据中找到最佳的伪对是可能的。此外，对抗性损失有助于减少转换的特征序列的过度平滑。我们用门控CNN配置一个CycleGAN，并用身份映射丢失来训练它。这允许映射功能捕获顺序和分层结构，同时保留语言信息。我们在一个并行数据的VC任务上评估了我们的方法。客观评价表明，转换后的特征序列在全局方差和调制谱方面接近自然。主观评价显示转换语音的质量与使用并行数据的有利条件下基于GMM的方法所获得的质量相当。

##### URL
[https://arxiv.org/abs/1711.11293](https://arxiv.org/abs/1711.11293)

