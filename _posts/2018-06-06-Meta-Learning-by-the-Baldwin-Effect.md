---
layout: post
title: "Meta Learning by the Baldwin Effect"
date: 2018-06-06 08:39:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Chrisantha Thomas Fernando, Jakub Sygnowski, Simon Osindero, Jane Wang, Tom Schaul, Denis Teplyashin, Pablo Sprechmann, Alexander Pritzel, Andrei A. Rusu
mathjax: true
---

* content
{:toc}

##### Abstract
The scope of the Baldwin effect was recently called into question by two papers that closely examined the seminal work of Hinton and Nowlan. To this date there has been no demonstration of its necessity in empirically challenging tasks. Here we show that the Baldwin effect is capable of evolving few-shot supervised and reinforcement learning mechanisms, by shaping the hyperparameters and the initial parameters of deep learning algorithms. Furthermore it can genetically accommodate strong learning biases on the same set of problems as a recent machine learning algorithm called MAML "Model Agnostic Meta-Learning" which uses second-order gradients instead of evolution to learn a set of reference parameters (initial weights) that can allow rapid adaptation to tasks sampled from a distribution. Whilst in simple cases MAML is more data efficient than the Baldwin effect, the Baldwin effect is more general in that it does not require gradients to be backpropagated to the reference parameters or hyperparameters, and permits effectively any number of gradient updates in the inner loop. The Baldwin effect learns strong learning dependent biases, rather than purely genetically accommodating fixed behaviours in a learning independent manner.

##### Abstract (translated by Google)
鲍德温效应的范围最近受到两篇关于Hinton和Nowlan开创性工作的论文的质疑。迄今为止，没有证据表明它在经验性挑战性任务中的必要性。在这里我们展示了鲍德温效应能够通过塑造超参数和深度学习算法的初始参数来演变少量监督和强化学习机制。此外，它可以遗传地适应与最近的机器学习算法（称为MAML“模型不可知论元学习”）相同的一组问题的强烈学习偏见，该算法使用二阶梯度而不是进化学习一组参考参数（初始权重）可以快速适应从分配中抽取的任务。虽然在简单的情况下，MAML比Baldwin效应更具数据效率，但Baldwin效应更为广泛，因为它不需要将梯度反向传播给参考参数或超参数，并且可以在内部循环中有效地执行任何数量的梯度更新。鲍德温效应学习强烈的学习依赖偏差，而不是以独立于学习方式的纯粹遗传学适应固定行为。

##### URL
[http://arxiv.org/abs/1806.07917](http://arxiv.org/abs/1806.07917)

##### PDF
[http://arxiv.org/pdf/1806.07917](http://arxiv.org/pdf/1806.07917)

