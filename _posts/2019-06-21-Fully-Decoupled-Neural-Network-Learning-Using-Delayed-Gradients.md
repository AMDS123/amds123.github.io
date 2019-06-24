---
layout: post
title: "Fully Decoupled Neural Network Learning Using Delayed Gradients"
date: 2019-06-21 13:02:35
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Huiping Zhuang, Yi Wang, Qinglai Liu, Zhiping Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Using the back-propagation (BP) to train neural networks requires a sequential passing of the activations and the gradients, which forces the network modules to work in a synchronous fashion. This has been recognized as the lockings (i.e., the forward, backward and update lockings) inherited from the BP. In this paper, we propose a fully decoupled training scheme using delayed gradients (FDG) to break all these lockings. The proposed method splits a neural network into multiple modules that are trained independently and asynchronously in different GPUs. We also introduce a gradient shrinking process to reduce the stale gradient effect caused by the delayed gradients. In addition, we prove that the proposed FDG algorithm guarantees a statistical convergence during training. Experiments are conducted by training deep convolutional neural networks to perform classification tasks on benchmark datasets. The proposed FDG is able to train very deep networks (&gt;100 layers) and very large networks (&gt;35 million parameters) with significant speed gains while outperforming the state-of-the-art methods and the standard BP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09108](http://arxiv.org/abs/1906.09108)

##### PDF
[http://arxiv.org/pdf/1906.09108](http://arxiv.org/pdf/1906.09108)

