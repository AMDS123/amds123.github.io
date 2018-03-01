---
layout: post
title: "Pomegranate: fast and flexible probabilistic modeling in python"
date: 2018-02-27 23:43:16
categories: arXiv_AI
tags: arXiv_AI
author: Jacob Schreiber
mathjax: true
---

* content
{:toc}

##### Abstract
We present pomegranate, an open source machine learning package for probabilistic modeling in Python. Probabilistic modeling encompasses a wide range of methods that explicitly describe uncertainty using probability distributions. Three widely used probabilistic models implemented in pomegranate are general mixture models, hidden Markov models, and Bayesian networks. A primary focus of pomegranate is to abstract away the complexities of training models from their definition. This allows users to focus on specifying the correct model for their application instead of being limited by their understanding of the underlying algorithms. An aspect of this focus involves the collection of additive sufficient statistics from data sets as a strategy for training models. This approach trivially enables many useful learning strategies, such as out-of-core learning, minibatch learning, and semi-supervised learning, without requiring the user to consider how to partition data or modify the algorithms to handle these tasks themselves. pomegranate is written in Cython to speed up calculations and releases the global interpreter lock to allow for built-in multithreaded parallelism, making it competitive with---or outperform---other implementations of similar algorithms. This paper presents an overview of the design choices in pomegranate, and how they have enabled complex features to be supported by simple code.

##### Abstract (translated by Google)
我们提供石榴，一个用于Python中概率建模的开源机器学习包。概率建模涵盖了使用概率分布明确描述不确定性的各种方法。在石榴中实施的三种广泛使用的概率模型是一般混合模型，隐马尔可夫模型和贝叶斯网络。石榴的主要焦点是从他们的定义中提取出训练模型的复杂性。这允许用户专注于为其应用程序指定正确的模型，而不是受其对底层算法的理解所限制。这一重点的一个方面涉及从数据集合中收集足够的加法统计数据作为训练模型的一种策略。这种方法不需要用户考虑如何划分数据或修改算法来自己处理这些任务，这种方法平凡地实现了许多有用的学习策略，例如外核学习，小批次学习和半监督学习。石榴是用Cython编写的，以加速计算并释放全局解释器锁以允许内置的多线程并行机制，使其具有竞争性---或优于其他类似算法的其他实现。本文概述了石榴的设计选择，以及它们如何使复杂功能得到简单代码的支持。

##### URL
[http://arxiv.org/abs/1711.00137](http://arxiv.org/abs/1711.00137)

##### PDF
[http://arxiv.org/pdf/1711.00137](http://arxiv.org/pdf/1711.00137)

