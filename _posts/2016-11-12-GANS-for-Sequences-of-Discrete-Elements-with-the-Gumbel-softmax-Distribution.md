---
layout: post
title: "GANS for Sequences of Discrete Elements with the Gumbel-softmax Distribution"
date: 2016-11-12 22:54:45
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN RNN
author: Matt J. Kusner, José Miguel Hernández-Lobato
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GAN) have limitations when the goal is to generate sequences of discrete elements. The reason for this is that samples from a distribution on discrete objects such as the multinomial are not differentiable with respect to the distribution parameters. This problem can be avoided by using the Gumbel-softmax distribution, which is a continuous approximation to a multinomial distribution parameterized in terms of the softmax function. In this work, we evaluate the performance of GANs based on recurrent neural networks with Gumbel-softmax output distributions in the task of generating sequences of discrete elements.

##### Abstract (translated by Google)
当目标是生成离散元素的序列时，生成对抗网络（GAN）具有局限性。其原因在于，来自诸如多项式之类的离散对象上的分布的样本关于分布参数是不可区分的。这个问题可以通过使用Gumbel-softmax分布来避免，这个分布是对softmax函数参数化的多项分布的连续逼近。在这项工作中，我们评估基于Gumbel-softmax输出分布的递归神经网络的GAN在生成离散元素序列任务中的性能。

##### URL
[https://arxiv.org/abs/1611.04051](https://arxiv.org/abs/1611.04051)

##### PDF
[https://arxiv.org/pdf/1611.04051](https://arxiv.org/pdf/1611.04051)

