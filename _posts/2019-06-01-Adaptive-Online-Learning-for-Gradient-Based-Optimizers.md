---
layout: post
title: "Adaptive Online Learning for Gradient-Based Optimizers"
date: 2019-06-01 21:04:31
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Saeed Masoudian, Ali Arabzadeh, Mahdi Jafari Siavoshani, Milad Jalal, Alireza Amouzad
mathjax: true
---

* content
{:toc}

##### Abstract
As application demands for online convex optimization accelerate, the need for designing new methods that simultaneously cover a large class of convex functions and impose the lowest possible regret is highly rising. Known online optimization methods usually perform well only in specific settings, and their performance depends highly on the geometry of the decision space and cost functions. However, in practice, lack of such geometric information leads to confusion in using the appropriate algorithm. To address this issue, some adaptive methods have been proposed that focus on adaptively learning parameters such as step size, Lipschitz constant, and strong convexity coefficient, or on specific parametric families such as quadratic regularizers. In this work, we generalize these methods and propose a framework that competes with the best algorithm in a family of expert algorithms. Our framework includes many of the well-known adaptive methods including MetaGrad, MetaGrad+C, and Ader. We also introduce a second algorithm that computationally outperforms our first algorithm with at most a constant factor increase in regret. Finally, as a representative application of our proposed algorithm, we study the problem of learning the best regularizer from a family of regularizers for Online Mirror Descent. Empirically, we support our theoretical findings in the problem of learning the best regularizer on the simplex and $l_2$-ball in a multiclass learning problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00290](http://arxiv.org/abs/1906.00290)

##### PDF
[http://arxiv.org/pdf/1906.00290](http://arxiv.org/pdf/1906.00290)

