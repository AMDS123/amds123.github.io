---
layout: post
title: "Invariant Representations for Noisy Speech Recognition"
date: 2016-11-27 22:20:51
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Speech_Recognition Classification Recognition
author: Dmitriy Serdyuk, Kartik Audhkhasi, Philémon Brakel, Bhuvana Ramabhadran, Samuel Thomas, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Modern automatic speech recognition (ASR) systems need to be robust under acoustic variability arising from environmental, speaker, channel, and recording conditions. Ensuring such robustness to variability is a challenge in modern day neural network-based ASR systems, especially when all types of variability are not seen during training. We attempt to address this problem by encouraging the neural network acoustic model to learn invariant feature representations. We use ideas from recent research on image generation using Generative Adversarial Networks and domain adaptation ideas extending adversarial gradient-based training. A recent work from Ganin et al. proposes to use adversarial training for image domain adaptation by using an intermediate representation from the main target classification network to deteriorate the domain classifier performance through a separate neural network. Our work focuses on investigating neural architectures which produce representations invariant to noise conditions for ASR. We evaluate the proposed architecture on the Aurora-4 task, a popular benchmark for noise robust ASR. We show that our method generalizes better than the standard multi-condition training especially when only a few noise categories are seen during training.

##### Abstract (translated by Google)
现代自动语音识别（ASR）系统需要在由环境，扬声器，声道和录音条件引起的声学可变性下保持稳健。在现代神经网络的ASR系统中，确保对可变性的这种鲁棒性是一个挑战，特别是在训练期间没有看到所有类型的可变性。我们试图通过鼓励神经网络声学模型来学习不变特征表示来解决这个问题。我们使用最近的关于图像生成的研究中的想法，使用生成对抗网络以及扩展基于梯度的对抗训练的领域适应思想。甘宁等人最近的工作。提出通过使用来自主目标分类网络的中间表示来使用对抗训练进行图像域自适应，以通过单独的神经网络使域分类器性能劣化。我们的工作重点是调查神经架构产生代表不变噪声条件的ASR。我们评估在Aurora-4任务上提出的架构，这是噪声稳健ASR的流行基准。我们表明，我们的方法比标准的多条件训练更好地推广，特别是在训练期间只看到少数噪声类别。

##### URL
[https://arxiv.org/abs/1612.01928](https://arxiv.org/abs/1612.01928)

##### PDF
[https://arxiv.org/pdf/1612.01928](https://arxiv.org/pdf/1612.01928)

