---
layout: post
title: "Meta-Learning Acquisition Functions for Bayesian Optimization"
date: 2019-04-04 16:27:06
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization
author: Michael Volpp, Lukas Fr&#xf6;hlich, Andreas Doerr, Frank Hutter, Christian Daniel
mathjax: true
---

* content
{:toc}

##### Abstract
Many practical applications of machine learning require data-efficient black-box function optimization, e.g., to identify hyperparameters or process settings. However, readily available algorithms are typically designed to be universal optimizers and are, thus, often suboptimal for specific tasks. We therefore propose a method to learn optimizers which are automatically adapted to a given class of objective functions, e.g., in the context of sim-to-real applications. Instead of learning optimization from scratch, the proposed approach is firmly based within the famous Bayesian optimization framework. Only the acquisition function (AF) is replaced by a learned neural network and therefore the resulting algorithm is still able to exploit the proven generalization capabilities of Gaussian processes. We present experiments on several simulated as well as on a sim-to-real transfer task. The results show that the learned optimizers (1) consistently perform better than or on-par with known AFs on general function classes and (2) can automatically identify structural properties of a function class using cheap simulations and transfer this knowledge to adapt rapidly to real hardware tasks, thereby significantly outperforming existing problem-agnostic AFs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02642](http://arxiv.org/abs/1904.02642)

##### PDF
[http://arxiv.org/pdf/1904.02642](http://arxiv.org/pdf/1904.02642)

