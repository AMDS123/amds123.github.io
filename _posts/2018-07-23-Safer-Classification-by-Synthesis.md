---
layout: post
title: "Safer Classification by Synthesis"
date: 2018-07-23 23:47:59
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Classification
author: William Wang, Angelina Wang, Aviv Tamar, Xi Chen, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
The discriminative approach to classification using deep neural networks has become the de-facto standard in various fields. Complementing recent reservations about safety against adversarial examples, we show that conventional discriminative methods can easily be fooled to provide incorrect labels with very high confidence to out of distribution examples. We posit that a generative approach is the natural remedy for this problem, and propose a method for classification using generative models. At training time, we learn a generative model for each class, while at test time, given an example to classify, we query each generator for its most similar generation, and select the class corresponding to the most similar one. Our approach is general and can be used with expressive models such as GANs and VAEs. At test time, our method accurately "knows when it does not know," and provides resilience to out of distribution examples while maintaining competitive performance for standard examples.

##### Abstract (translated by Google)
使用深度神经网络进行分类的判别方法已成为各个领域的事实标准。作为对最近对抗对抗性示例的保留的补充，我们表明传统的判别方法很容易被愚弄，以提供对分布式示例具有非常高置信度的不正确标签。我们认为生成方法是解决这个问题的自然方法，并提出了一种使用生成模型进行分类的方法。在训练时，我们学习每个类的生成模型，在测试时，给出一个分类的例子，我们查询每个生成器的最相似的生成，并选择与最相似的类相对应的类。我们的方法是通用的，可以用于表达模型，如GAN和VAE。在测试时，我们的方法准确地“知道何时不知道”，并为分发示例提供弹性，同时保持标准示例的竞争性能。

##### URL
[http://arxiv.org/abs/1711.08534](http://arxiv.org/abs/1711.08534)

##### PDF
[http://arxiv.org/pdf/1711.08534](http://arxiv.org/pdf/1711.08534)

