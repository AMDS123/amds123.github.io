---
layout: post
title: "Communication-Free Parallel Supervised Topic Models"
date: 2017-08-10 02:03:52
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Lee Gao, Ronghuo Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Embarrassingly (communication-free) parallel Markov chain Monte Carlo (MCMC) methods are commonly used in learning graphical models. However, MCMC cannot be directly applied in learning topic models because of the quasi-ergodicity problem caused by multimodal distribution of topics. In this paper, we develop an embarrassingly parallel MCMC algorithm for sLDA. Our algorithm works by switching the order of sampled topics combination and labeling variable prediction in sLDA, in which it overcomes the quasi-ergodicity problem because high-dimension topics that follow a multimodal distribution are projected into one-dimension document labels that follow a unimodal distribution. Our empirical experiments confirm that the out-of-sample prediction performance using our embarrassingly parallel algorithm is comparable to non-parallel sLDA while the computation time is significantly reduced.

##### Abstract (translated by Google)
令人尴尬的（无通信）并行马尔可夫链蒙特卡洛（MCMC）方法通常用于学习图形模型。但由于主题多模态分布引起的准遍历问题，MCMC不能直接用于学习主题模型。在本文中，我们为sLDA开发了一个令人尴尬的并行MCMC算法。我们的算法通过在sLDA中切换采样主题组合的顺序和标记可变预测来工作，其中它克服了准遍历性问题，因为遵循多模式分布的高维主题被投影到遵循单峰分布的一维文档标签中。我们的经验性实验证实，使用我们令人尴尬的并行算法的样本外预测性能与非并行sLDA相当，同时计算时间显着减少。

##### URL
[https://arxiv.org/abs/1708.03052](https://arxiv.org/abs/1708.03052)

##### PDF
[https://arxiv.org/pdf/1708.03052](https://arxiv.org/pdf/1708.03052)

