---
layout: post
title: "Diagnostic Visualization for Deep Neural Networks Using Stochastic Gradient Langevin Dynamics"
date: 2018-12-11 18:43:52
categories: arXiv_AI
tags: arXiv_AI GAN
author: Biye Jiang, David M. Chan, Tianhao Zhang, John F. Canny
mathjax: true
---

* content
{:toc}

##### Abstract
The internal states of most deep neural networks are difficult to interpret, which makes diagnosis and debugging during training challenging. Activation maximization methods are widely used, but lead to multiple optima and are hard to interpret (appear noise-like) for complex neurons. Image-based methods use maximally-activating image regions which are easier to interpret, but do not provide pixel-level insight into why the neuron responds to them. In this work we introduce an MCMC method: Langevin Dynamics Activation Maximization (LDAM), which is designed for diagnostic visualization. LDAM provides two affordances in combination: the ability to explore the set of maximally activating pre-images, and the ability to trade-off interpretability and pixel-level accuracy using a GAN-style discriminator as a regularizer. We present case studies on MNIST, CIFAR and ImageNet datasets exploring these trade-offs. Finally we show that diagnostic visualization using LDAM leads to a novel insight into the parameter averaging method for deep net training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04604](http://arxiv.org/abs/1812.04604)

##### PDF
[http://arxiv.org/pdf/1812.04604](http://arxiv.org/pdf/1812.04604)

