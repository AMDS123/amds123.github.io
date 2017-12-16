---
layout: post
title: "Multi-Agent Diverse Generative Adversarial Networks"
date: 2017-04-10 15:26:23
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Arnab Ghosh, Viveka Kulharia, Vinay Namboodiri, Philip H. S. Torr, Puneet K. Dokania
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes an intuitive generalization to the Generative Adversarial Networks (GANs) to generate samples while capturing diverse modes of the true data distribution. Firstly, we propose a very simple and intuitive multi-agent GAN architecture that incorporates multiple generators capable of generating samples from high probability modes. Secondly, in order to enforce different generators to generate samples from diverse modes, we propose two extensions to the standard GAN objective function. (1) We augment the generator specific GAN objective function with a diversity enforcing term that encourage different generators to generate diverse samples using a user-defined similarity based function. (2) We modify the discriminator objective function where along with finding the real and fake samples, the discriminator has to predict the generator which generated the given fake sample. Intuitively, in order to succeed in this task, the discriminator must learn to push different generators towards different identifiable modes. Our framework is generalizable in the sense that it can be easily combined with other existing variants of GANs to produce diverse samples. Experimentally we show that our framework is able to produce high quality diverse samples for the challenging tasks such as image/face generation and image-to-image translation. We also show that it is capable of learning a better feature representation in an unsupervised setting.

##### Abstract (translated by Google)
本文描述了生成敌对网络（GAN）的直观推广，以生成样本，同时捕获真实数据分布的不同模式。首先，我们提出了一个非常简单直观的多代理GAN架构，它包含了多个能够从高概率模式生成样本的生成器。其次，为了强制不同的发生器产生不同模式的样本，我们提出了对标准GAN目标函数的两个扩展。 （1）我们用一个多样性强化术语来增强发生器特定的GAN目标函数，鼓励不同的发生器使用用户定义的基于相似性的函数来生成不同的样本。 （2）修改鉴别器目标函数，在找到真假样本的同时，鉴别器必须预测产生给定假样本的发生器。直觉上，为了在这个任务中取得成功，鉴别者必须学会将不同的发生器推向不同的可识别模式。我们的框架是可以概括的，因为它可以很容易地与其他现有的GAN变体结合起来生成不同的样本。在实验上，我们展示了我们的框架能够生成高质量的多样化样本，用于诸如图像/脸部生成和图像到图像转换等具有挑战性的任务。我们还表明它能够在无人监督的环境中学习更好的特征表示。

##### URL
[https://arxiv.org/abs/1704.02906](https://arxiv.org/abs/1704.02906)

##### PDF
[https://arxiv.org/pdf/1704.02906](https://arxiv.org/pdf/1704.02906)

