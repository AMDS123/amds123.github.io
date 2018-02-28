---
layout: post
title: "Adversarial Active Learning for Deep Networks: a Margin Based Approach"
date: 2018-02-27 12:02:33
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Melanie Ducoffe, Frederic Precioso
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new active learning strategy designed for deep neural networks. The goal is to minimize the number of data annotation queried from an oracle during training. Previous active learning strategies scalable for deep networks were mostly based on uncertain sample selection. In this work, we focus on examples lying close to the decision boundary. Based on theoretical works on margin theory for active learning, we know that such examples may help to considerably decrease the number of annotations. While measuring the exact distance to the decision boundaries is intractable, we propose to rely on adversarial examples. We do not consider anymore them as a threat instead we exploit the information they provide on the distribution of the input space in order to approximate the distance to decision boundaries. We demonstrate empirically that adversarial active queries yield faster convergence of CNNs trained on MNIST, the Shoe-Bag and the Quick-Draw datasets.

##### Abstract (translated by Google)
我们提出了一种为深度神经网络设计的新的主动学习策略。目标是最大限度地减少训练期间从oracle预先查询的数据注释的数量。先前的针对深度网络可扩展的主动学习策略主要基于不确定的样本选择。在这项工作中，我们将重点放在靠近决策边界的例子。根据关于主动学习的边际理论的理论着作，我们知道这样的例子可能有助于大大减少注释的数量。虽然测量到决策边界的确切距离是棘手的，但我们建议依靠敌对的例子。我们不再将它们视为威胁，而是利用它们提供的关于输入空间分布的信息，以便将距离逼近决策边界。我们凭经验证明，敌对活跃查询可以更快地收敛MNIST，Shoe-Bag和Quick-Draw数据集上训练的CNNs。

##### URL
[https://arxiv.org/abs/1802.09841](https://arxiv.org/abs/1802.09841)

##### PDF
[https://arxiv.org/pdf/1802.09841](https://arxiv.org/pdf/1802.09841)

