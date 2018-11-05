---
layout: post
title: "Dantzig Selector with an Approximately Optimal Denoising Matrix and its Application to Reinforcement Learning"
date: 2018-11-02 16:15:14
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Optimization
author: Bo Liu, Luwan Zhang, Ji Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Dantzig Selector (DS) is widely used in compressed sensing and sparse learning for feature selection and sparse signal recovery. Since the DS formulation is essentially a linear programming optimization, many existing linear programming solvers can be simply applied for scaling up. The DS formulation can be explained as a basis pursuit denoising problem, wherein the data matrix (or measurement matrix) is employed as the denoising matrix to eliminate the observation noise. However, we notice that the data matrix may not be the optimal denoising matrix, as shown by a simple counter-example. This motivates us to pursue a better denoising matrix for defining a general DS formulation. We first define the optimal denoising matrix through a minimax optimization, which turns out to be an NPhard problem. To make the problem computationally tractable, we propose a novel algorithm, termed as Optimal Denoising Dantzig Selector (ODDS), to approximately estimate the optimal denoising matrix. Empirical experiments validate the proposed method. Finally, a novel sparse reinforcement learning algorithm is formulated by extending the proposed ODDS algorithm to temporal difference learning, and empirical experimental results demonstrate to outperform the conventional vanilla DS-TD algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00958](http://arxiv.org/abs/1811.00958)

##### PDF
[http://arxiv.org/pdf/1811.00958](http://arxiv.org/pdf/1811.00958)

