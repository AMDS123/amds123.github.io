---
layout: post
title: "Scalable Meta-Learning for Bayesian Optimization"
date: 2018-02-06 21:02:59
categories: arXiv_AI
tags: arXiv_AI Face Optimization
author: Matthias Feurer, Benjamin Letham, Eytan Bakshy
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian optimization has become a standard technique for hyperparameter optimization, including data-intensive models such as deep neural networks that may take days or weeks to train. We consider the setting where previous optimization runs are available, and we wish to use their results to warm-start a new optimization run. We develop an ensemble model that can incorporate the results of past optimization runs, while avoiding the poor scaling that comes with putting all results into a single Gaussian process model. The ensemble combines models from past runs according to estimates of their generalization performance on the current optimization. Results from a large collection of hyperparameter optimization benchmark problems and from optimization of a production computer vision platform at Facebook show that the ensemble can substantially reduce the time it takes to obtain near-optimal configurations, and is useful for warm-starting expensive searches or running quick re-optimizations.

##### Abstract (translated by Google)
贝叶斯优化已成为超参数优化的标准技术，包括数据密集型模型，如可能需要几天或几周训练的深度神经网络。我们考虑先前的优化运行可用的设置，并且我们希望使用它们的结果来热启动一个新的优化运行。我们开发了一个集合模型，可以结合过去的优化运行的结果，同时避免将所有结果放入单个高斯过程模型所带来的可扩展性差。根据对当前优化的泛化性能的估计，集合将来自过去运行的模型组合在一起。来自大量超参数优化基准测试问题的结果以及在Facebook上优化生产计算机视觉平台的结果表明，该集成可以大大缩短获得接近最佳配置所需的时间，并且对于热启动昂贵的搜索或运行快速重新优化。

##### URL
[http://arxiv.org/abs/1802.02219](http://arxiv.org/abs/1802.02219)

##### PDF
[http://arxiv.org/pdf/1802.02219](http://arxiv.org/pdf/1802.02219)

