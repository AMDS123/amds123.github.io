---
layout: post
title: "MAP Inference via L2-Sphere Linear Program Reformulation"
date: 2019-05-09 03:47:15
categories: arXiv_CV
tags: arXiv_CV Inference
author: Baoyuan Wu, Li Shen, Bernard Ghanem, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Maximum a posteriori (MAP) inference is an important task for graphical models. Due to complex dependencies among variables in realistic model, finding an exact solution for MAP inference is often intractable. Thus, many approximation methods have been developed, among which the linear programming (LP) relaxation based methods show promising performance. However, one major drawback of LP relaxation is that it is possible to give fractional solutions. Instead of presenting a tighter relaxation, in this work we propose a continuous but equivalent reformulation of the original MAP inference problem, called LS-LP. We add the L2-sphere constraint onto the original LP relaxation, leading to an intersected space with the local marginal polytope that is equivalent to the space of all valid integer label configurations. Thus, LS-LP is equivalent to the original MAP inference problem. We propose a perturbed alternating direction method of multipliers (ADMM) algorithm to optimize the LS-LP problem, by adding a sufficiently small perturbation epsilon onto the objective function and constraints. We prove that the perturbed ADMM algorithm globally converges to the epsilon-Karush-Kuhn-Tucker (epsilon-KKT) point of the LS-LP problem. The convergence rate will also be analyzed. Experiments on several benchmark datasets from Probabilistic Inference Challenge (PIC 2011) and OpenGM 2 show competitive performance of our proposed method against state-of-the-art MAP inference methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03433](http://arxiv.org/abs/1905.03433)

##### PDF
[http://arxiv.org/pdf/1905.03433](http://arxiv.org/pdf/1905.03433)

