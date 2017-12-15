---
layout: post
title: "Data-free parameter pruning for Deep Neural Networks"
date: 2015-07-22 12:18:21
categories: arXiv_CV
tags: arXiv_CV
author: Suraj Srinivas, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural nets (NNs) with millions of parameters are at the heart of many state-of-the-art computer vision systems today. However, recent works have shown that much smaller models can achieve similar levels of performance. In this work, we address the problem of pruning parameters in a trained NN model. Instead of removing individual weights one at a time as done in previous works, we remove one neuron at a time. We show how similar neurons are redundant, and propose a systematic way to remove them. Our experiments in pruning the densely connected layers show that we can remove upto 85\% of the total parameters in an MNIST-trained network, and about 35\% for AlexNet without significantly affecting performance. Our method can be applied on top of most networks with a fully connected layer to give a smaller network.

##### Abstract (translated by Google)
具有数百万参数的深度神经网络（NN）是当今许多最先进的计算机视觉系统的核心。然而，最近的作品表明，更小的模型可以达到类似的性能水平。在这项工作中，我们解决了在训练的NN模型中修剪参数的问题。我们不是像以前的作品那样逐个去除单个的权重，而是一次去除一个神经元。我们展示了如何类似的神经元是多余的，并提出一个系统的方法来消除它们。我们在修剪密集连接层的实验表明，我们可以去除MNIST训练网络中总参数的85％，而AlexNet则可以去除35％左右，而不会显着影响性能。我们的方法可以应用在大多数具有完全连接层的网络之上，从而使网络更小。

##### URL
[https://arxiv.org/abs/1507.06149](https://arxiv.org/abs/1507.06149)

##### PDF
[https://arxiv.org/pdf/1507.06149](https://arxiv.org/pdf/1507.06149)

