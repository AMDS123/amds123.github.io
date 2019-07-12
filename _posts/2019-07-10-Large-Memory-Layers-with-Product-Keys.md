---
layout: post
title: "Large Memory Layers with Product Keys"
date: 2019-07-10 14:52:12
categories: arXiv_CL
tags: arXiv_CL Inference Language_Model Prediction
author: Guillaume Lample, Alexandre Sablayrolles, Marc&#x27;Aurelio Ranzato, Ludovic Denoyer, Herv&#xe9; J&#xe9;gou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a structured memory which can be easily integrated into a neural network. The memory is very large by design and therefore significantly increases the capacity of the architecture, by up to a billion parameters with a negligible computational overhead. Its design and access pattern is based on product keys, which enable fast and exact nearest neighbor search. The ability to increase the number of parameters while keeping the same computational budget lets the overall system strike a better trade-off between prediction accuracy and computation efficiency both at training and test time. This memory layer allows us to tackle very large scale language modeling tasks. In our experiments we consider a dataset with up to 30 billion words, and we plug our memory layer in a state-of-the-art transformer-based architecture. In particular, we found that a memory augmented model with only 12 layers outperforms a baseline transformer model with 24 layers, while being twice faster at inference time. We release our code for reproducibility purposes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05242](http://arxiv.org/abs/1907.05242)

##### PDF
[http://arxiv.org/pdf/1907.05242](http://arxiv.org/pdf/1907.05242)

