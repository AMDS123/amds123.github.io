---
layout: post
title: "Multi-target Voice Conversion without Parallel Data by Adversarially Learning Disentangled Audio Representations"
date: 2018-06-24 18:11:02
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Embedding
author: Ju-chieh Chou, Cheng-chieh Yeh, Hung-yi Lee, Lin-shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, cycle-consistent adversarial network (Cycle-GAN) has been successfully applied to voice conversion to a different speaker without parallel data, although in those approaches an individual model is needed for each target speaker. In this paper, we propose an adversarial learning framework for voice conversion, with which a single model can be trained to convert the voice to many different speakers, all without parallel data, by separating the speaker characteristics from the linguistic content in speech signals. An autoencoder is first trained to extract speaker-independent latent representations and speaker embedding separately using another auxiliary speaker classifier to regularize the latent representation. The decoder then takes the speaker-independent latent representation and the target speaker embedding as the input to generate the voice of the target speaker with the linguistic content of the source utterance. The quality of decoder output is further improved by patching with the residual signal produced by another pair of generator and discriminator. A target speaker set size of 20 was tested in the preliminary experiments, and very good voice quality was obtained. Conventional voice conversion metrics are reported. We also show that the speaker information has been properly reduced from the latent representations.

##### Abstract (translated by Google)
最近，循环一致的对抗网络（Cycle-GAN）已经成功地应用于不具有并行数据的不同说话者的语音转换，但是在这些方法中，每个目标说话者需要单独的模型。在本文中，我们提出了一种用于语音转换的对抗性学习框架，通过将语音信号中的语言内容与讲话者特征分离，可以训练单个模型以将语音转换为许多不同的讲话者，而不需要并行数据。首先训练自编码器，以使用另一辅助说话者分类器分别提取与说话者无关的潜在表示和说话者嵌入以规范潜在表示。解码器然后将与说话者无关的潜在表示和目标说话者嵌入作为输入来生成具有源话语的语言内容的目标说话者的语音。通过修补由另一对发生器和鉴别器产生的残留信号，解码器输出的质量得到进一步改善。在初步实验中测试了目标扬声器组大小为20，并且获得了非常好的语音质量。报告传统的语音转换指标。我们还表明，演讲者的信息已经从潜在的表示中适当地减少了。

##### URL
[http://arxiv.org/abs/1804.02812](http://arxiv.org/abs/1804.02812)

##### PDF
[http://arxiv.org/pdf/1804.02812](http://arxiv.org/pdf/1804.02812)

