---
layout: post
title: "Neural Networks for Predicting Algorithm Runtime Distributions"
date: 2018-05-09 07:42:29
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Katharina Eggensperger, Marius Lindauer, Frank Hutter
mathjax: true
---

* content
{:toc}

##### Abstract
Many state-of-the-art algorithms for solving hard combinatorial problems in artificial intelligence (AI) include elements of stochasticity that lead to high variations in runtime, even for a fixed problem instance. Knowledge about the resulting runtime distributions (RTDs) of algorithms on given problem instances can be exploited in various meta-algorithmic procedures, such as algorithm selection, portfolios, and randomized restarts. Previous work has shown that machine learning can be used to individually predict mean, median and variance of RTDs. To establish a new state-of-the-art in predicting RTDs, we demonstrate that the parameters of an RTD should be learned jointly and that neural networks can do this well by directly optimizing the likelihood of an RTD given runtime observations. In an empirical study involving five algorithms for SAT solving and AI planning, we show that neural networks predict the true RTDs of unseen instances better than previous methods, and can even do so when only few runtime observations are available per training instance.

##### Abstract (translated by Google)
许多用于解决人工智能（AI）中的硬组合问题的最先进的算法包括导致运行时变化很大的随机性元素，即使对于固定的问题实例。关于给定问题实例上算法的最终运行时分布（RTD）的知识可以在各种元算法过程中使用，例如算法选择，投资组合和随机重启。以前的工作表明，机器学习可以用来单独预测RTD的平均值，中值和方差。为了建立预测RTD的最新技术，我们证明RTD的参数应该共同学习，并且神经网络可以通过直接优化给定运行时观察RTD的可能性来做到这一点。在一个涉及SAT求解和人工智能规划的五种算法的实证研究中，我们展示了神经网络比以前的方法更好地预测了看不见的实例的真实RTD，并且甚至可以在每个训练实例只有少数运行时观察值的情况下这样做。

##### URL
[http://arxiv.org/abs/1709.07615](http://arxiv.org/abs/1709.07615)

##### PDF
[http://arxiv.org/pdf/1709.07615](http://arxiv.org/pdf/1709.07615)

