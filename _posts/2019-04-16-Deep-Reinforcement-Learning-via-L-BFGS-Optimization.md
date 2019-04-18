---
layout: post
title: "Deep Reinforcement Learning via L-BFGS Optimization"
date: 2019-04-16 20:52:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Gradient_Descent
author: Jacob Rafati, Roummel F. Marcia
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement Learning (RL) algorithms allow artificial agents to improve their action selections so as to increase rewarding experiences in their environments. Deep Reinforcement Learning algorithms require solving a nonconvex and nonlinear unconstrained optimization problem. Methods for solving the optimization problems in deep RL are restricted to the class of first-order algorithms, such as stochastic gradient descent (SGD). The major drawback of the SGD methods is that they have the undesirable effect of not escaping saddle points and their performance can be seriously obstructed by ill-conditioning. Furthermore, SGD methods require exhaustive trial and error to fine-tune many learning parameters. Using second derivative information can result in improved convergence properties, but computing the Hessian matrix for large-scale problems is not practical. Quasi-Newton methods require only first-order gradient information, like SGD, but they can construct a low rank approximation of the Hessian matrix and result in superlinear convergence. The limited-memory Broyden-Fletcher-Goldfarb-Shanno (L-BFGS) approach is one of the most popular quasi-Newton methods that construct positive definite Hessian approximations. In this paper, we introduce an efficient optimization method, based on the limited memory BFGS quasi-Newton method using line search strategy -- as an alternative to SGD methods. Our method bridges the disparity between first order methods and second order methods by continuing to use gradient information to calculate a low-rank Hessian approximations. We provide formal convergence analysis as well as empirical results on a subset of the classic ATARI 2600 games. Our results show a robust convergence with preferred generalization characteristics, as well as fast training time and no need for the experience replaying mechanism.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02693](http://arxiv.org/abs/1811.02693)

##### PDF
[http://arxiv.org/pdf/1811.02693](http://arxiv.org/pdf/1811.02693)

