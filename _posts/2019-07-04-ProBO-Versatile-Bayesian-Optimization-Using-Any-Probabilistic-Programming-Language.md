---
layout: post
title: "ProBO: Versatile Bayesian Optimization Using Any Probabilistic Programming Language"
date: 2019-07-04 17:49:10
categories: arXiv_AI
tags: arXiv_AI Optimization Inference
author: Willie Neiswanger, Kirthevasan Kandasamy, Barnabas Poczos, Jeff Schneider, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Optimizing an expensive-to-query function is a common task in science and engineering, where it is beneficial to keep the number of queries to a minimum. A popular strategy is Bayesian optimization (BO), which leverages probabilistic models for this task. Most BO today uses Gaussian processes (GPs), or a few other surrogate models. However, there is a broad set of Bayesian modeling techniques that could be used to capture complex systems and reduce the number of queries in BO. Probabilistic programming languages (PPLs) are modern tools that allow for flexible model definition, prior specification, model composition, and automatic inference. In this paper, we develop ProBO, a BO procedure that uses only standard operations common to most PPLs. This allows a user to drop in a model built with an arbitrary PPL and use it directly in BO. We describe acquisition functions for ProBO, and strategies for efficiently optimizing these functions given complex models or costly inference procedures. Using existing PPLs, we implement new models to aid in a few challenging optimization settings, and demonstrate these on model hyperparameter and architecture search tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11515](http://arxiv.org/abs/1901.11515)

##### PDF
[http://arxiv.org/pdf/1901.11515](http://arxiv.org/pdf/1901.11515)

