---
layout: post
title: "Efficient Algorithms for Outlier-Robust Regression"
date: 2018-03-08 18:30:31
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization
author: Adam Klivans, Pravesh K. Kothari, Raghu Meka
mathjax: true
---

* content
{:toc}

##### Abstract
We give the first polynomial-time algorithm for performing linear or polynomial regression resilient to adversarial corruptions in both examples and labels. 
 Given a sufficiently large (polynomial-size) training set drawn i.i.d. from distribution D and subsequently corrupted on some fraction of points, our algorithm outputs a linear function whose squared error is close to the squared error of the best-fitting linear function with respect to D, assuming that the marginal distribution of D over the input space is \emph{certifiably hypercontractive}. This natural property is satisfied by many well-studied distributions such as Gaussian, strongly log-concave distributions and, uniform distribution on the hypercube among others. We also give a simple statistical lower bound showing that some distributional assumption is necessary to succeed in this setting. 
 These results are the first of their kind and were not known to be even information-theoretically possible prior to our work. 
 Our approach is based on the sum-of-squares (SoS) method and is inspired by the recent applications of the method for parameter recovery problems in unsupervised learning. Our algorithm can be seen as a natural convex relaxation of the following conceptually simple non-convex optimization problem: find a linear function and a large subset of the input corrupted sample such that the least squares loss of the function over the subset is minimized over all possible large subsets.

##### Abstract (translated by Google)
我们给出了第一个多项式时间算法，用于执行线性或多项式回归，这些回归对于示例和标签中的对抗性破坏是有弹性的。
 给定一个足够大的（多项式大小）训练集i.i.d.从分布D开始，然后在一些点上受到破坏，我们的算法输出一个线性函数，其平方误差接近最佳拟合线性函数关于D的平方误差，假设D在输入空间上的边际分布是\ emph {certifiably hypercontractive}。这种自然属性由许多经过深入研究的分布满足，如高斯分布，强对数凹分布和超立方体中的均匀分布等。我们还给出了一个简单的统计下限，表明一些分布假设对于在这种情况下取​​得成功是必要的。
 这些结果是第一次，在我们的工作之前并不知道甚至是信息 - 理论上可能的。
 我们的方法基于平方和（SoS）方法，并受到该方法在无监督学习中参数恢复问题的最近应用的启发。我们的算法可以看作是以下概念上简单的非凸优化问题的自然凸松弛：找到输入损坏样本的线性函数和大子集，使得函数在子集上的最小平方损失最小化可能的大型子集。

##### URL
[http://arxiv.org/abs/1803.03241](http://arxiv.org/abs/1803.03241)

##### PDF
[http://arxiv.org/pdf/1803.03241](http://arxiv.org/pdf/1803.03241)

