---
layout: post
title: "Simultaneous Adversarial Training - Learn from Others Mistakes"
date: 2018-07-21 08:28:21
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Zukang Liao
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples are maliciously tweaked images that can easily fool machine learning techniques, such as neural networks, but they are normally not visually distinguishable for human beings. One of the main approaches to solve this problem is to retrain the networks using those adversarial examples, namely adversarial training. However, standard adversarial training might not actually change the decision boundaries but cause the problem of gradient masking, resulting in a weaker ability to generate adversarial examples. Therefore, it cannot alleviate the problem of black-box attacks, where adversarial examples generated from other networks can transfer to the targeted one. In order to reduce the problem of black-box attacks, we propose a novel method that allows two networks to learn from each others' adversarial examples and become resilient to black-box attacks. We also combine this method with a simple domain adaptation to further improve the performance.

##### Abstract (translated by Google)
对抗性示例是恶意调整的图像，可以轻易地欺骗机器学习技术，例如神经网络，但它们通常在视觉上不能与人类区分开来。解决这个问题的主要方法之一是使用那些对抗性的例子，即对抗性训练来重新训练网络。但是，标准对抗训练实际上可能不会改变决策边界，但会导致梯度掩蔽问题，从而导致生成对抗性示例的能力较弱。因此，它无法缓解黑盒攻击的问题，其中从其他网络生成的对抗性示例可以转移到目标网络。为了减少黑盒攻击的问题，我们提出了一种新方法，允许两个网络相互学习对抗的例子，并对黑盒攻击具有弹性。我们还将此方法与简单的域适配相结合，以进一步提高性能。

##### URL
[http://arxiv.org/abs/1807.08108](http://arxiv.org/abs/1807.08108)

##### PDF
[http://arxiv.org/pdf/1807.08108](http://arxiv.org/pdf/1807.08108)

