---
layout: post
title: "Three Factors Influencing Minima in SGD"
date: 2018-09-13 09:29:55
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent Relation
author: Stanis&#x142;aw Jastrz&#x119;bski, Zachary Kenton, Devansh Arpit, Nicolas Ballas, Asja Fischer, Yoshua Bengio, Amos Storkey
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the dynamical and convergent properties of stochastic gradient descent (SGD) applied to Deep Neural Networks (DNNs). Characterizing the relation between learning rate, batch size and the properties of the final minima, such as width or generalization, remains an open question. In order to tackle this problem we investigate the previously proposed approximation of SGD by a stochastic differential equation (SDE). We theoretically argue that three factors - learning rate, batch size and gradient covariance - influence the minima found by SGD. In particular we find that the ratio of learning rate to batch size is a key determinant of SGD dynamics and of the width of the final minima, and that higher values of the ratio lead to wider minima and often better generalization. We confirm these findings experimentally. Further, we include experiments which show that learning rate schedules can be replaced with batch size schedules and that the ratio of learning rate to batch size is an important factor influencing the memorization process.

##### Abstract (translated by Google)
我们研究了应用于深度神经网络（DNN）的随机梯度下降（SGD）的动态和收敛性质。表征学习率，批量大小和最终最小值的属性（例如宽度或概括）之间的关系仍然是一个悬而未决的问题。为了解决这个问题，我们通过随机微分方程（SDE）研究了先前提出的SGD近似。我们理论上认为三个因素 - 学习率，批量大小和梯度协方差 - 影响SGD发现的最小值。特别地，我们发现学习率与批量大小的比率是SGD动力学和最终最小值宽度的关键决定因素，并且该比率的较高值导致更宽的最小值并且通常更好地推广。我们通过实验证实这些发现。此外，我们还包括一些实验，这些实验表明学习率计划可以用批量大小计划替换，学习率与批量大小的比率是影响记忆过程的重要因素。

##### URL
[http://arxiv.org/abs/1711.04623](http://arxiv.org/abs/1711.04623)

##### PDF
[http://arxiv.org/pdf/1711.04623](http://arxiv.org/pdf/1711.04623)

