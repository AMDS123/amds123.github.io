---
layout: post
title: "Flow-GAN: Combining Maximum Likelihood and Adversarial Learning in Generative Models"
date: 2018-01-03 21:47:01
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Quantitative
author: Aditya Grover, Manik Dhar, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial learning of probabilistic models has recently emerged as a promising alternative to maximum likelihood. Implicit models such as generative adversarial networks (GAN) often generate better samples compared to explicit models trained by maximum likelihood. Yet, GANs sidestep the characterization of an explicit density which makes quantitative evaluations challenging. To bridge this gap, we propose Flow-GANs, a generative adversarial network for which we can perform exact likelihood evaluation, thus supporting both adversarial and maximum likelihood training. When trained adversarially, Flow-GANs generate high-quality samples but attain extremely poor log-likelihood scores, inferior even to a mixture model memorizing the training data; the opposite is true when trained by maximum likelihood. Results on MNIST and CIFAR-10 demonstrate that hybrid training can attain high held-out likelihoods while retaining visual fidelity in the generated samples.

##### Abstract (translated by Google)
概率模型的对抗学习最近已经成为最大可能的有希望的替代方案。诸如生成对抗网络（GAN）的隐式模型与通过最大可能性训练的显式模型相比通常产生更好的样本。然而，GAN避开了定性评估具有挑战性的明确密度的特征。为弥补这一差距，我们提出了Flow-GANs，这是一个生成对抗性网络，我们可以进行准确的可能性评估，从而支持敌对和最大似然训练。当对抗训练时，Flow-GAN产生高质量的样本，但得到极差的对数似然分数，即使对于记忆训练数据的混合模型也是如此;最大可能性训练时则相反。 MNIST和CIFAR-10的结果表明，混合培训可以在保留所生成的样本中的视觉保真度的同时获得高度保留的可能性。

##### URL
[http://arxiv.org/abs/1705.08868](http://arxiv.org/abs/1705.08868)

##### PDF
[http://arxiv.org/pdf/1705.08868](http://arxiv.org/pdf/1705.08868)

