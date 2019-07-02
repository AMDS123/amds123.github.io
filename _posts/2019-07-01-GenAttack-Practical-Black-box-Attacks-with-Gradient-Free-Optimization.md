---
layout: post
title: "GenAttack: Practical Black-box Attacks with Gradient-Free Optimization"
date: 2019-07-01 00:32:03
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization Recognition
author: Moustafa Alzantot, Yash Sharma, Supriyo Chakraborty, Huan Zhang, Cho-Jui Hsieh, Mani Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are vulnerable to adversarial examples, even in the black-box setting, where the attacker is restricted solely to query access. Existing black-box approaches to generating adversarial examples typically require a significant number of queries, either for training a substitute network or performing gradient estimation. We introduce GenAttack, a gradient-free optimization technique that uses genetic algorithms for synthesizing adversarial examples in the black-box setting. Our experiments on different datasets (MNIST, CIFAR-10, and ImageNet) show that GenAttack can successfully generate visually imperceptible adversarial examples against state-of-the-art image recognition models with orders of magnitude fewer queries than previous approaches. Against MNIST and CIFAR-10 models, GenAttack required roughly 2,126 and 2,568 times fewer queries respectively, than ZOO, the prior state-of-the-art black-box attack. In order to scale up the attack to large-scale high-dimensional ImageNet models, we perform a series of optimizations that further improve the query efficiency of our attack leading to 237 times fewer queries against the Inception-v3 model than ZOO. Furthermore, we show that GenAttack can successfully attack some state-of-the-art ImageNet defenses, including ensemble adversarial training and non-differentiable or randomized input transformations. Our results suggest that evolutionary algorithms open up a promising area of research into effective black-box attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.11090](http://arxiv.org/abs/1805.11090)

##### PDF
[http://arxiv.org/pdf/1805.11090](http://arxiv.org/pdf/1805.11090)

