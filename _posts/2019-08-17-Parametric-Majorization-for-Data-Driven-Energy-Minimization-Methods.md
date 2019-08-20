---
layout: post
title: "Parametric Majorization for Data-Driven Energy Minimization Methods"
date: 2019-08-17 00:10:41
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Jonas Geiping, Michael Moeller
mathjax: true
---

* content
{:toc}

##### Abstract
Energy minimization methods are a classical tool in a multitude of computer vision applications. While they are interpretable and well-studied, their regularity assumptions are difficult to design by hand. Deep learning techniques on the other hand are purely data-driven, often provide excellent results, but are very difficult to constrain to predefined physical or safety-critical models. A possible combination between the two approaches is to design a parametric energy and train the free parameters in such a way that minimizers of the energy correspond to desired solution on a set of training examples. Unfortunately, such formulations typically lead to bi-level optimization problems, on which common optimization algorithms are difficult to scale to modern requirements in data processing and efficiency. In this work, we present a new strategy to optimize these bi-level problems. We investigate surrogate single-level problems that majorize the target problems and can be implemented with existing tools, leading to efficient algorithms without collapse of the energy function. This framework of strategies enables new avenues to the training of parameterized energy minimization models from large data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06209](http://arxiv.org/abs/1908.06209)

##### PDF
[http://arxiv.org/pdf/1908.06209](http://arxiv.org/pdf/1908.06209)

