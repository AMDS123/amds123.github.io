---
layout: post
title: "Stochastic Gradient/Mirror Descent: Minimax Optimality and Implicit Regularization"
date: 2018-06-04 04:53:00
categories: arXiv_AI
tags: arXiv_AI Regularization Optimization Deep_Learning Gradient_Descent
author: Navid Azizan, Babak Hassibi
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic descent methods (of the gradient and mirror varieties) have become increasingly popular in optimization. In fact, it is now widely recognized that the success of deep learning is not only due to the special deep architecture of the models, but also due to the behavior of the stochastic descent methods used, which play a key role in reaching "good" solutions that generalize well to unseen data. In an attempt to shed some light on why this is the case, we revisit some minimax properties of stochastic gradient descent (SGD) on the square loss of linear models---originally developed in the 1990's---and extend them to \emph{generic} stochastic mirror descent (SMD) algorithms on \emph{general} loss functions and \emph{nonlinear} models. In particular, we show that there is a fundamental identity which holds for SMD (and SGD) under very general conditions, and that this identity implies the minimax optimality of SMD (and SGD) with sufficiently small step size, for a general class of loss functions and general nonlinear models. We further show that this identity can be used to naturally establish other properties of SMD (and SGD), such as convergence and \emph{implicit regularization} for over-parameterized linear models, which have been shown in certain cases in the literature. We also show how this identity can be used in the so-called "highly over-parameterized" nonlinear setting to provide insights into why SMD (and SGD) may have similar convergence and implicit regularization properties for deep learning.

##### Abstract (translated by Google)
随机下降法（渐变和镜像变体）在优化中越来越受欢迎。事实上，现在人们普遍认识到，深度学习的成功不仅是由于模型的特殊深层架构，而且也是由于所使用的随机下降方法的行为，这些方法在达到“良好”这些解决方案能够很好地将数据转化为不可见。为了说明为什么会出现这种情况，我们重新研究了随机梯度下降（SGD）的一些极小极小性质，它们是线性模型的平方损失 - 最初是在90年代开发的 - 然后将它们扩展到\ emph {通用}随机镜像下降（SMD）算法在\ emph {通用}损失函数和\ emph {非线性}模型上。具体而言，我们表明在非常一般的条件下存在SMD（和SGD）的基本身份，并且此身份意味着具有足够小的步长的SMD（和SGD）的最小极大值最优性，用于一般类别的损失函数和一般非线性模型。我们进一步表明，这种身份可以用来自然地建立SMD（和SGD）的其他性质，例如在参数化线性模型中的收敛和\ emph {隐式正则化}，这在文献中的某些情况下已经显示。我们还展示了如何在所谓的“高度超参数化”非线性设置中使用这种身份，以深入了解为什么SMD（和SGD）可能具有相似的收敛性和深度学习的隐式正则化特性。

##### URL
[http://arxiv.org/abs/1806.00952](http://arxiv.org/abs/1806.00952)

##### PDF
[http://arxiv.org/pdf/1806.00952](http://arxiv.org/pdf/1806.00952)

