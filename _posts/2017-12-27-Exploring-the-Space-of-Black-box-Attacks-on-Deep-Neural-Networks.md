---
layout: post
title: "Exploring the Space of Black-box Attacks on Deep Neural Networks"
date: 2017-12-27 04:39:02
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Arjun Nitin Bhagoji, Warren He, Bo Li, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
Existing black-box attacks on deep neural networks (DNNs) so far have largely focused on transferability, where an adversarial instance generated for a locally trained model can "transfer" to attack other learning models. In this paper, we propose novel Gradient Estimation black-box attacks for adversaries with query access to the target model's class probabilities, which do not rely on transferability. We also propose strategies to decouple the number of queries required to generate each adversarial sample from the dimensionality of the input. An iterative variant of our attack achieves close to 100% adversarial success rates for both targeted and untargeted attacks on DNNs. We carry out extensive experiments for a thorough comparative evaluation of black-box attacks and show that the proposed Gradient Estimation attacks outperform all transferability based black-box attacks we tested on both MNIST and CIFAR-10 datasets, achieving adversarial success rates similar to well known, state-of-the-art white-box attacks. We also apply the Gradient Estimation attacks successfully against a real-world Content Moderation classifier hosted by Clarifai. Furthermore, we evaluate black-box attacks against state-of-the-art defenses. We show that the Gradient Estimation attacks are very effective even against these defenses.

##### Abstract (translated by Google)
迄今为止，对深度神经网络（DNN）的现有黑盒攻击主要集中在可转移性上，其中针对本地训练模型产生的对抗实例可以“转移”来攻击其他学习模型。在本文中，我们提出了新的梯度估计黑箱攻击的查询访问目标模型的类概率，不依赖于可转移性。我们还提出了一些策略，用于从输入的维度中分离生成每个敌对样本所需的查询数量。我们攻击的迭代变体实现了对DNN的有针对性和非攻击性攻击接近100％的对抗成功率。我们进行了广泛的实验，对黑盒攻击进行了彻底的比较评估，并且表明所提出的梯度估计攻击优于我们在MNIST和CIFAR-10数据集上测试的所有基于黑盒攻击的可转移性，实现了与众所周知的对抗成功率，最先进的白盒攻击。我们还成功地将Gradient Estimation攻击应用于由Clarifai托管的真实世界Content Moderation分类器。此外，我们评估黑匣子攻击与最先进的防御。我们表明，即使对这些防御措施，梯度估计攻击也是非常有效的。

##### URL
[http://arxiv.org/abs/1712.09491](http://arxiv.org/abs/1712.09491)

##### PDF
[http://arxiv.org/pdf/1712.09491](http://arxiv.org/pdf/1712.09491)

