---
layout: post
title: "Stochastic natural gradient descent draws posterior samples in function space"
date: 2018-06-25 17:47:42
categories: arXiv_AI
tags: arXiv_AI Prediction Gradient_Descent
author: Samuel L. Smith, Daniel Duckworth, Quoc V. Le, Jascha Sohl-Dickstein
mathjax: true
---

* content
{:toc}

##### Abstract
Natural gradient descent (NGD) minimises the cost function on a Riemannian manifold whose metric is defined by the Fisher information. In this work, we prove that if the model predictions on the training set approach the true conditional distribution of labels given inputs, then the noise inherent in minibatch gradients causes the stationary distribution of NGD to approach a Bayesian posterior, whose temperature $T \approx \epsilon N/(2B)$ is controlled by the learning rate $\epsilon$, training set size $N$ and batch size $B$. The parameter-dependence of the Fisher metric introduces an implicit prior over the parameters, which we identify as the well-known Jeffreys prior. To support our claims, we show that the distribution of samples from NGD is close to the Laplace approximation to the posterior when $T = 1$. Furthermore, the test loss of ensembles drawn using NGD falls rapidly as we increase the batch size until $B \approx \epsilon N/2$, while above this point the test loss is constant or rises slowly.

##### Abstract (translated by Google)
自然梯度下降（NGD）最小化黎曼流形上的费用函数，其度量由Fisher信息定义。在这项工作中，我们证明了如果训练集上的模型预测接近给定输入的标签的真实条件分布，那么小批次梯度中固有的噪声会导致NGD的平稳分布接近贝叶斯后验，其温度为$ T \ approx \ N /（2B）$由学习率$ \ epsilon $，训练集大小$ N $和批量大小$ B $控制。 Fisher度量的参数依赖性引入了一个超过参数的隐式先验值，我们将其确定为众所周知的Jeffreys先前的参数。为了支持我们的说法，我们证明了当$ T = 1 $时，来自NGD的样本分布接近于后验的拉普拉斯近似。此外，随着我​​们增加批量大小，直到$ B \ approx \ epsilon N / 2 $，使用NGD绘制的乐团的测试损失迅速下降，而在此点以上时，测试损失保持不变或缓慢上升。

##### URL
[http://arxiv.org/abs/1806.09597](http://arxiv.org/abs/1806.09597)

##### PDF
[http://arxiv.org/pdf/1806.09597](http://arxiv.org/pdf/1806.09597)

