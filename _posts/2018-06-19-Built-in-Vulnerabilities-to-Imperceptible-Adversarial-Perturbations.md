---
layout: post
title: "Built-in Vulnerabilities to Imperceptible Adversarial Perturbations"
date: 2018-06-19 18:12:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Thomas Tanay, Jerone T. A. Andrews, Lewis D. Griffin
mathjax: true
---

* content
{:toc}

##### Abstract
Designing models that are robust to small adversarial perturbations of their inputs has proven remarkably difficult. In this work we show that the reverse problem---making models more vulnerable---is surprisingly easy. After presenting some proofs of concept on MNIST, we introduce a generic tilting attack that injects vulnerabilities into the linear layers of pre-trained networks without affecting their performance on natural data. We illustrate this attack on a multilayer perceptron trained on SVHN and use it to design a stand-alone adversarial module which we call a steganogram decoder. Finally, we show on CIFAR-10 that a state-of-the-art network can be trained to misclassify images in the presence of imperceptible backdoor signals. These different results suggest that adversarial perturbations are not always informative of the true features used by a model.

##### Abstract (translated by Google)
事实证明，设计对其输入的小型敌对扰动具有鲁棒性的模型非常困难。在这项工作中，我们证明了相反的问题---使模型更易受到攻击---这是非常容易的。在MNIST上提出了一些概念验证之后，我们引入了一种通用倾斜攻击，它将漏洞插入预先训练好的网络的线性层，而不会影响其在自然数据上的性能。我们通过SVHN训练的多层感知器来说明这种攻击，并用它来设计一个我们称之为隐写解码器的独立对抗模块。最后，我们在CIFAR-10上展示了一个最先进的网络可以训练成在存在不可察觉的后门信号的情况下对图像进行错误分类。这些不同的结果表明对抗性扰动并不总是提供模型使用的真实特征的信息。

##### URL
[http://arxiv.org/abs/1806.07409](http://arxiv.org/abs/1806.07409)

##### PDF
[http://arxiv.org/pdf/1806.07409](http://arxiv.org/pdf/1806.07409)

