---
layout: post
title: "Memory Replay GANs: learning to generate images from new categories without forgetting"
date: 2018-09-06 15:45:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Chenshen Wu, Luis Herranz, Xialei Liu, Yaxing Wang, Joost van de Weijer, Bogdan Raducanu
mathjax: true
---

* content
{:toc}

##### Abstract
Previous works on sequential learning address the problem of forgetting in discriminative models. In this paper we consider the case of generative models. In particular, we investigate generative adversarial networks (GANs) in the task of learning new categories in a sequential fashion. We first show that sequential fine tuning renders the network unable to properly generate images from previous categories (i.e. forgetting). Addressing this problem, we propose Memory Replay GANs (MeRGANs), a conditional GAN framework that integrates a memory replay generator. We study two methods to prevent forgetting by leveraging these replays, namely joint training with replay and replay alignment. Qualitative and quantitative experimental results in MNIST, SVHN and LSUN datasets show that our memory replay approach can generate competitive images while significantly mitigating the forgetting of previous categories

##### Abstract (translated by Google)
以前关于顺序学习的工作解决了在判别模型中遗忘的问题。在本文中，我们考虑生成模型的情况。特别是，我们研究生成对抗网络（GAN），以顺序方式学习新类别。我们首先表明，顺序微调使网络无法正确生成先前类别的图像（即遗忘）。针对这个问题，我们提出了内存重放GAN（MeRGAN），一种集成内存重放生成器的条件GAN框架。我们研究了两种通过利用这些重放来防止遗忘的方法，即重播和重放对齐的联合训练。 MNIST，SVHN和LSUN数据集中的定性和定量实验结果表明，我们的记忆重放方法可以生成竞争图像，同时显着减少以前类别的遗忘

##### URL
[http://arxiv.org/abs/1809.02058](http://arxiv.org/abs/1809.02058)

##### PDF
[http://arxiv.org/pdf/1809.02058](http://arxiv.org/pdf/1809.02058)

