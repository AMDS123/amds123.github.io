---
layout: post
title: "Nonlinear Distributional Gradient Temporal-Difference Learning"
date: 2019-01-27 04:58:44
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Chao Qu, Shie Mannor, Huan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We devise a distributional variant of gradient temporal-difference (TD) learning. Distributional reinforcement learning has been demonstrated to outperform the regular one in the recent study \citep{bellemare2017distributional}. In the policy evaluation setting, we design two new algorithms called distributional GTD2 and distributional TDC using the Cram{\'e}r distance on the distributional version of the Bellman error objective function, which inherits advantages of both the nonlinear gradient TD algorithms and the distributional RL approach. In the control setting, we propose the distributional Greedy-GQ using the similar derivation. We prove the asymptotic almost-sure convergence of distributional GTD2 and TDC to a local optimal solution for general smooth function approximators, which includes neural networks that have been widely used in recent study to solve the real-life RL problems. In each step, the computational complexities of above three algorithms are linear w.r.t.\ the number of the parameters of the function approximator, thus can be implemented efficiently for neural networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07732](http://arxiv.org/abs/1805.07732)

##### PDF
[http://arxiv.org/pdf/1805.07732](http://arxiv.org/pdf/1805.07732)

