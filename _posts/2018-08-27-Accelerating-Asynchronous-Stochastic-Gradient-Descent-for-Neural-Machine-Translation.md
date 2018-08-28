---
layout: post
title: "Accelerating Asynchronous Stochastic Gradient Descent for Neural Machine Translation"
date: 2018-08-27 14:19:18
categories: arXiv_CL
tags: arXiv_CL Gradient_Descent
author: Nikolay Bogoychev, Marcin Junczys-Dowmunt, Kenneth Heafield, Alham Fikri Aji
mathjax: true
---

* content
{:toc}

##### Abstract
In order to extract the best possible performance from asynchronous stochastic gradient descent one must increase the mini-batch size and scale the learning rate accordingly. In order to achieve further speedup we introduce a technique that delays gradient updates effectively increasing the mini-batch size. Unfortunately with the increase of mini-batch size we worsen the stale gradient problem in asynchronous stochastic gradient descent (SGD) which makes the model convergence poor. We introduce local optimizers which mitigate the stale gradient problem and together with fine tuning our momentum we are able to train a shallow machine translation system 27% faster than an optimized baseline with negligible penalty in BLEU.

##### Abstract (translated by Google)
为了从异步随机梯度下降中提取最佳性能，必须增加小批量大小并相应地缩放学习率。为了实现进一步加速，我们引入了一种延迟梯度更新的技术，有效地增加了小批量。不幸的是，随着小批量大小的增加，我们使异步随机梯度下降（SGD）中的陈旧梯度问题恶化，这使得模型收敛性变差。我们引入了局部优化器来缓解陈旧的梯度问题，并且通过微调我们的动量，我们能够训练浅机器翻译系统比优化基线快27％，而BLEU中的罚分可以忽略不计。

##### URL
[http://arxiv.org/abs/1808.08859](http://arxiv.org/abs/1808.08859)

##### PDF
[http://arxiv.org/pdf/1808.08859](http://arxiv.org/pdf/1808.08859)

