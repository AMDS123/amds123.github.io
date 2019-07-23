---
layout: post
title: "Accelerating Experimental Design by Incorporating Experimenter Hunches"
date: 2019-07-22 00:48:24
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Cheng Li, Santu Rana, Sunil Gupta, Vu Nguyen, Svetha Venkatesh, Alessandra Sutti, David Rubin, Teo Slezak, Murray Height, Mazher Mohammed, Ian Gibson
mathjax: true
---

* content
{:toc}

##### Abstract
Experimental design is a process of obtaining a product with target property via experimentation. Bayesian optimization offers a sample-efficient tool for experimental design when experiments are expensive. Often, expert experimenters have 'hunches' about the behavior of the experimental system, offering potentials to further improve the efficiency. In this paper, we consider per-variable monotonic trend in the underlying property that results in a unimodal trend in those variables for a target value optimization. For example, sweetness of a candy is monotonic to the sugar content. However, to obtain a target sweetness, the utility of the sugar content becomes a unimodal function, which peaks at the value giving the target sweetness and falls off both ways. In this paper, we propose a novel method to solve such problems that achieves two main objectives: a) the monotonicity information is used to the fullest extent possible, whilst ensuring that b) the convergence guarantee remains intact. This is achieved by a two-stage Gaussian process modeling, where the first stage uses the monotonicity trend to model the underlying property, and the second stage uses `virtual' samples, sampled from the first, to model the target value optimization function. The process is made theoretically consistent by adding appropriate adjustment factor in the posterior computation, necessitated because of using the `virtual' samples. The proposed method is evaluated through both simulations and real world experimental design problems of a) new short polymer fiber with the target length, and b) designing of a new three dimensional porous scaffolding with a target porosity. In all scenarios our method demonstrates faster convergence than the basic Bayesian optimization approach not using such `hunches'.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09065](http://arxiv.org/abs/1907.09065)

##### PDF
[http://arxiv.org/pdf/1907.09065](http://arxiv.org/pdf/1907.09065)

