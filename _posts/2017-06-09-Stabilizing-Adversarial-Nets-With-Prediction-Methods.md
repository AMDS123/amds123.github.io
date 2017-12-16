---
layout: post
title: "Stabilizing Adversarial Nets With Prediction Methods"
date: 2017-06-09 04:22:35
categories: arXiv_CV
tags: arXiv_CV Adversarial Prediction Gradient_Descent
author: Abhay Yadav, Sohil Shah, Zheng Xu, David Jacobs, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial neural networks solve many important problems in data science, but are notoriously difficult to train. These difficulties come from the fact that optimal weights for adversarial nets correspond to saddle points, and not minimizers, of the loss function. The alternating stochastic gradient methods typically used for such problems do not reliably converge to saddle points, and when convergence does happen it is often highly sensitive to learning rates. We propose a simple modification of stochastic gradient descent that stabilizes adversarial networks. We show, both in theory and practice, that the proposed method reliably converges to saddle points. This makes adversarial networks less likely to "collapse", and enables faster training with larger learning rates.

##### Abstract (translated by Google)
敌对神经网络解决了数据科学中的许多重要问题，但难以训练。这些困难来自对抗网络的最佳权重对应于损失函数的鞍点而不是最小值的事实。通常用于这些问题的交替随机梯度方法不能可靠地收敛到鞍点，并且当收敛发生时，对学习速率通常是高度敏感的。我们提出了一个稳定敌对网络的随机梯度下降的简单修改。我们在理论和实践中都表明，所提出的方法可靠地收敛到鞍点。这使得敌对网络不太可能“崩溃”，并且以更高的学习速度实现更快的训练。

##### URL
[https://arxiv.org/abs/1705.07364](https://arxiv.org/abs/1705.07364)

##### PDF
[https://arxiv.org/pdf/1705.07364](https://arxiv.org/pdf/1705.07364)

