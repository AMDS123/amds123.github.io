---
layout: post
title: "Lock-Free Parallel Perceptron for Graph-based Dependency Parsing"
date: 2017-03-02 13:49:23
categories: arXiv_SD
tags: arXiv_SD
author: Xu Sun, Shuming Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Dependency parsing is an important NLP task. A popular approach for dependency parsing is structured perceptron. Still, graph-based dependency parsing has the time complexity of $O(n^3)$, and it suffers from slow training. To deal with this problem, we propose a parallel algorithm called parallel perceptron. The parallel algorithm can make full use of a multi-core computer which saves a lot of training time. Based on experiments we observe that dependency parsing with parallel perceptron can achieve 8-fold faster training speed than traditional structured perceptron methods when using 10 threads, and with no loss at all in accuracy.

##### Abstract (translated by Google)
依赖分析是一个重要的NLP任务。一种常用的依赖解析方法是结构感知器。尽管如此，基于图的依赖分析的时间复杂度为$ O（n ^ 3）$，而且训练速度慢。为了解决这个问题，我们提出了一种称为并行感知器的并行算法。并行算法可以充分利用多核计算机，节省大量的训练时间。在实验的基础上，我们观察到，使用10个线程的情况下，使用并行感知器进行依赖性分析的速度比传统的结构化感知器方法提高了8倍，而且完全没有损失。

##### URL
[https://arxiv.org/abs/1703.00782](https://arxiv.org/abs/1703.00782)

##### PDF
[https://arxiv.org/pdf/1703.00782](https://arxiv.org/pdf/1703.00782)

