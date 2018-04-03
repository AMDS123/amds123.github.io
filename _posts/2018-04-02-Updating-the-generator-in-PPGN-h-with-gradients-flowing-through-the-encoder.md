---
layout: post
title: "Updating the generator in PPGN-h with gradients flowing through the encoder"
date: 2018-04-02 17:22:00
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Hesam Pakdaman
mathjax: true
---

* content
{:toc}

##### Abstract
The Generative Adversarial Network framework has shown success in implicitly modeling data distributions and is able to generate realistic samples. Its architecture is comprised of a generator, which produces fake data that superficially seem to belong to the real data distribution, and a discriminator which is to distinguish fake from genuine samples. The Noiseless Joint Plug &amp; Play model offers an extension to the framework by simultaneously training autoencoders. This model uses a pre-trained encoder as a feature extractor, feeding the generator with global information. Using the Plug &amp; Play network as baseline, we design a new model by adding discriminators to the Plug &amp; Play architecture. These additional discriminators are trained to discern real and fake latent codes, which are the output of the encoder using genuine and generated inputs, respectively. We proceed to investigate whether this approach is viable. Experiments conducted for the MNIST manifold show that this indeed is the case.

##### Abstract (translated by Google)
生成敌对网络框架已经在隐式地建模数据分布方面取得了成功，并且能够生成逼真的样本。其架构由发生器组成，该发生器产生表面上似乎属于真实数据分布的假数据，以及区分伪造和真实样本的鉴别器。无噪音接头Plug＆amp; Play模型通过同时训练自动编码器提供了框架的扩展。该模型使用预先训练的编码器作为特征提取器，为发生器提供全局信息。使用Plug＆amp;以网络播放为基准，我们通过在Plug＆amp;插件中添加鉴别器来设计新模型。玩架构。这些附加的鉴别器被训练来识别真伪潜在的代码，它们分别是使用真实和产生的输入的编码器的输出。我们继续调查这种方法是否可行。针对MNIST歧管进行的实验表明确实如此。

##### URL
[http://arxiv.org/abs/1804.00630](http://arxiv.org/abs/1804.00630)

##### PDF
[http://arxiv.org/pdf/1804.00630](http://arxiv.org/pdf/1804.00630)

