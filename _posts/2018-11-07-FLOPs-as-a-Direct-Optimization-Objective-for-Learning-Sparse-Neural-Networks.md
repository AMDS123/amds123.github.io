---
layout: post
title: "FLOPs as a Direct Optimization Objective for Learning Sparse Neural Networks"
date: 2018-11-07 18:21:25
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Image_Classification Optimization Inference Classification
author: Raphael Tang, Ashutosh Adhikari, Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
There exists a plethora of techniques for inducing structured sparsity in parametric models during the optimization process, with the final goal of resource-efficient inference. However, to the best of our knowledge, none target a specific number of floating-point operations (FLOPs) as part of a single end-to-end optimization objective, despite reporting FLOPs as part of the results. Furthermore, a one-size-fits-all approach ignores realistic system constraints, which differ significantly between, say, a GPU and a mobile phone -- FLOPs on the former incur less latency than on the latter; thus, it is important for practitioners to be able to specify a target number of FLOPs during model compression. In this work, we extend a state-of-the-art technique to directly incorporate FLOPs as part of the optimization objective and show that, given a desired FLOPs requirement, different neural networks can be successfully trained for image classification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03060](http://arxiv.org/abs/1811.03060)

##### PDF
[http://arxiv.org/pdf/1811.03060](http://arxiv.org/pdf/1811.03060)

