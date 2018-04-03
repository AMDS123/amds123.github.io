---
layout: post
title: "A Multi-Discriminator CycleGAN for Unsupervised Non-Parallel Speech Domain Adaptation"
date: 2018-03-27 05:04:39
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Speech_Recognition Recognition
author: Ehsan Hosseini-Asl, Yingbo Zhou, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation plays an important role for speech recognition models, in particular, for domains that have low resources. We propose a novel generative model based on cyclic-consistent generative adversarial network (CycleGAN) for unsupervised non-parallel speech domain adaptation. The proposed model employs multiple independent discriminator on the power spectrogram, each in charge of different frequency bands. As a result we have 1) better discriminators that focuses on fine-grained details of the frequency features, and 2) a generator that is capable of generating more realistic domain adapted spectrogram. We demonstrate the effectiveness of our method on speech recognition with gender adaptation, where the model only have access to supervised data from one gender during training, but is evaluated on the other at testing time. Our model is able to achieve an average of $7.41\%$ on phoneme error rate, and $11.10\%$ word error rate relative performance improvement as compared to the baseline on TIMIT and WSJ dataset, respectively. Qualitatively, our model also generate more realistic sounding speech synthesis when conditioned on data from the other domain.

##### Abstract (translated by Google)
领域适应对于语音识别模型起着重要的作用，特别是对于资源不足的领域。我们提出了一种基于循环一致生成对抗网络（CycleGAN）的无监督非平行语音域适应的新型生成模型。所提出的模型在功率谱图上采用多个独立鉴别器，每个鉴别器负责不同的频带。因此，我们有1）更好的鉴别器，专注于频率特征的细粒度细节，以及2）能够产生更现实的域适应谱图的发生器。我们证明了我们的方法在性别适应性语音识别方面的有效性，其中模型只能在训练期间获得来自一个性别的监督数据，但是在测试时间被评估。与TIMIT和WSJ数据集的基线相比，我们的模型能够分别在音素错误率和$ 11.10 \％$字错误率相对性能改进方面分别实现7.41美元/％$的平均值。定性地说，我们的模型在处理来自其他领域的数据时也会产生更真实的声音语音合成。

##### URL
[http://arxiv.org/abs/1804.00522](http://arxiv.org/abs/1804.00522)

##### PDF
[http://arxiv.org/pdf/1804.00522](http://arxiv.org/pdf/1804.00522)

