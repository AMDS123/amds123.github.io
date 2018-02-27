---
layout: post
title: "A Modification of Particle Swarm Optimization using Random Walk"
date: 2018-02-26 13:27:37
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Rajesh Misra, Kumar S. Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Particle swarm optimization comes under lot of changes after James Kennedy and Russell Eberhart first proposes the idea in 1995. The changes has been done mainly on Inertia parameters in velocity updating equation so that the convergence rate will be higher. We are proposing a novel approach where particles movement will not be depend on its velocity rather it will be decided by constrained biased random walk of particles. In random walk every particles movement based on two significant parameters, one is random process like toss of a coin and other is how much displacement a particle should have. In our approach we exploit this idea by performing a biased random operation and based on the outcome of that random operation, PSO particles choose the direction of the path and move non-uniformly into the solution space. This constrained, non-uniform movement helps the random walking particle to converge quicker then classical PSO. In our constrained biased random walking approach, we no longer needed velocity term (Vi), rather we introduce a new parameter (K) which is a probabilistic function. No global best particle (PGbest), local best particle (PLbest), Constriction parameter (W) are required rather we use a new term called Ptarg which is loosely influenced by PGbest.We test our algorithm on five different benchmark functions, and also compare its performance with classical PSO and Quantum Particle Swarm Optimization (QPSO).This new approach have been shown significantly better than basic PSO and sometime outperform QPSO in terms of convergence, search space, number of iterations.

##### Abstract (translated by Google)
在James Kennedy和Russell Eberhart于1995年首次提出这个想法之后，粒子群优化问题发生了很多变化。这些变化主要是在速度更新方程中的惯性参数上进行的，因此收敛速度会更快。我们提出了一种新颖的方法，其中粒子运动不取决于其速度，而是由粒子的约束偏差随机游走决定。在随机游走基于两个重要参数的每个粒子运动时，一个是随机过程，就像掷硬币一样，另一个是粒子应该有多大的位移。在我们的方法中，我们通过执行偏置随机操作并基于随机操作的结果来利用这个想法，PSO粒子选择路径的方向并且非均匀地移动到解空间中。这种受约束的非均匀运动有助于随机行走粒子更快地收敛于经典PSO。在我们的约束有偏随机行走方法中，我们不再需要速度项（Vi），而是引入一个新的参数（K），它是一个概率函数。我们不需要全局最优粒子（PGbest），局部最优粒子（PLbest），缩小参数（W），而是使用一个名为Ptarg的新术语，它受PGbest的松散影响。我们在五个不同的基准函数上测试了我们的算法，其经典PSO和量子粒子群优化（QPSO）的性能。这种新方法已经显示出比基本PSO好得多，并且在收敛性，搜索空间，迭代次数等方面表现优于QPSO。

##### URL
[http://arxiv.org/abs/1711.10401](http://arxiv.org/abs/1711.10401)

##### PDF
[http://arxiv.org/pdf/1711.10401](http://arxiv.org/pdf/1711.10401)

