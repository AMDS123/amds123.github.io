---
layout: post
title: "It Takes Two: Adversarial Generator-Encoder Networks"
date: 2017-11-06 15:05:03
categories: arXiv_CV
tags: arXiv_CV Adversarial Inference
author: Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new autoencoder-type architecture that is trainable in an unsupervised mode, sustains both generation and inference, and has the quality of conditional and unconditional samples boosted by adversarial learning. Unlike previous hybrids of autoencoders and adversarial networks, the adversarial game in our approach is set up directly between the encoder and the generator, and no external mappings are trained in the process of learning. The game objective compares the divergences of each of the real and the generated data distributions with the prior distribution in the latent space. We show that direct generator-vs-encoder game leads to a tight coupling of the two components, resulting in samples and reconstructions of a comparable quality to some recently-proposed more complex architectures.

##### Abstract (translated by Google)
我们提出了一种新的自编码器型架构，可以在无监督模式下进行训练，同时支持生成和推理，并具有对抗性学习促进的有条件和无条件样本的质量。与以前的自编码器和敌对网络的混合体不同，我们的方法中的对抗性游戏是直接在编码器和生成器之间建立起来的，在学习过程中没有外部映射的训练。游戏目标比较每个实际和生成的数据分布与先验分布在潜在空间中的差异。我们展示了直接的发生器与编码器的游戏导致了两个组件的紧密耦合，导致样本和重建的质量与最近提出的一些更复杂的架构相当。

##### URL
[https://arxiv.org/abs/1704.02304](https://arxiv.org/abs/1704.02304)

##### PDF
[https://arxiv.org/pdf/1704.02304](https://arxiv.org/pdf/1704.02304)

