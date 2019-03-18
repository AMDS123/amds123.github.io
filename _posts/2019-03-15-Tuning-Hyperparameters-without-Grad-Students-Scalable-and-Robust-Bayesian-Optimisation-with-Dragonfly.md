---
layout: post
title: "Tuning Hyperparameters without Grad Students: Scalable and Robust Bayesian Optimisation with Dragonfly"
date: 2019-03-15 17:45:39
categories: arXiv_AI
tags: arXiv_AI
author: Kirthevasan Kandasamy, Karun Raju Vysyaraju, Willie Neiswanger, Biswajit Paria, Christopher R. Collins, Jeff Schneider, Barnabas Poczos, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian Optimisation (BO), refers to a suite of techniques for global optimisation of expensive black box functions, which use introspective Bayesian models of the function to efficiently find the optimum. While BO has been applied successfully in many applications, modern optimisation tasks usher in new challenges where conventional methods fail spectacularly. In this work, we present Dragonfly, an open source Python library for scalable and robust BO. Dragonfly incorporates multiple recently developed methods that allow BO to be applied in challenging real world settings; these include better methods for handling higher dimensional domains, methods for handling multi-fidelity evaluations when cheap approximations of an expensive function are available, methods for optimising over structured combinatorial spaces, such as the space of neural network architectures, and methods for handling parallel evaluations. Additionally, we develop new methodological improvements in BO for selecting the Bayesian model, selecting the acquisition function, and optimising over complex domains with different variable types and additional constraints. We compare Dragonfly to a suite of other packages and algorithms for global optimisation and demonstrate that when the above methods are integrated, they enable significant improvements in the performance of BO. The Dragonfly library is available at dragonfly.github.io.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06694](http://arxiv.org/abs/1903.06694)

##### PDF
[http://arxiv.org/pdf/1903.06694](http://arxiv.org/pdf/1903.06694)

