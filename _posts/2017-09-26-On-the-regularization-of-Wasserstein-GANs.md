---
layout: post
title: "On the regularization of Wasserstein GANs"
date: 2017-09-26 08:53:41
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Optimization
author: Henning Petzka, Asja Fischer, Denis Lukovnicov
mathjax: true
---

* content
{:toc}

##### Abstract
Since their invention, generative adversarial networks (GANs) have become a popular approach for learning to model a distribution of real (unlabeled) data. Convergence problems during training are overcome by Wasserstein GANs which minimize the distance between the model and the empirical distribution in terms of a different metric, but thereby introduce a Lipschitz constraint into the optimization problem. A simple way to enforce the Lipschitz constraint on the class of functions, which can be modeled by the neural network, is weight clipping. It was proposed that training can be improved by instead augmenting the loss by a regularization term that penalizes the deviation of the gradient of the critic (as a function of the network's input) from one. We present theoretical arguments why using a weaker regularization term enforcing the Lipschitz constraint is preferable. These arguments are supported by experimental results on toy data sets.

##### Abstract (translated by Google)
自发明以来，生成对抗网络（GAN）已成为学习模拟真实（未标记）数据分布的流行方法。在训练过程中的收敛问题可以通过Wasserstein GANs来克服，它可以通过一个不同的度量最小化模型和经验分布之间的距离，从而将Lipschitz约束引入优化问题。一个简单的方法来执行Lipschitz约束的功能类，可以模拟神经网络，是减重。有人提出，培训可以改善，而不是通过一个规范化的术语来增加损失，从而惩罚批评者的梯度（作为网络输入的函数）的偏差。我们提出理论上的论据，为什么使用强制Lipschitz约束的较弱正则化术语更可取。玩具数据集上的实验结果支持了这些论点。

##### URL
[https://arxiv.org/abs/1709.08894](https://arxiv.org/abs/1709.08894)

##### PDF
[https://arxiv.org/pdf/1709.08894](https://arxiv.org/pdf/1709.08894)

