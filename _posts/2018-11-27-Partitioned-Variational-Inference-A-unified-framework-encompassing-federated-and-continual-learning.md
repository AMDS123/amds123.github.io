---
layout: post
title: "Partitioned Variational Inference: A unified framework encompassing federated and continual learning"
date: 2018-11-27 19:16:00
categories: arXiv_AI
tags: arXiv_AI Knowledge Face Optimization Inference
author: Thang D. Bui, Cuong V. Nguyen, Siddharth Swaroop, Richard E. Turner
mathjax: true
---

* content
{:toc}

##### Abstract
Variational inference (VI) has become the method of choice for fitting many modern probabilistic models. However, practitioners are faced with a fragmented literature that offers a bewildering array of algorithmic options. First, the variational family. Second, the granularity of the updates e.g. whether the updates are local to each data point and employ message passing or global. Third, the method of optimization (bespoke or blackbox, closed-form or stochastic updates, etc.). This paper presents a new framework, termed Partitioned Variational Inference (PVI), that explicitly acknowledges these algorithmic dimensions of VI, unifies disparate literature, and provides guidance on usage. Crucially, the proposed PVI framework allows us to identify new ways of performing VI that are ideally suited to challenging learning scenarios including federated learning (where distributed computing is leveraged to process non-centralized data) and continual learning (where new data and tasks arrive over time and must be accommodated quickly). We showcase these new capabilities by developing communication-efficient federated training of Bayesian neural networks and continual learning for Gaussian process models with private pseudo-points. The new methods significantly outperform the state-of-the-art, whilst being almost as straightforward to implement as standard VI.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11206](http://arxiv.org/abs/1811.11206)

##### PDF
[http://arxiv.org/pdf/1811.11206](http://arxiv.org/pdf/1811.11206)

