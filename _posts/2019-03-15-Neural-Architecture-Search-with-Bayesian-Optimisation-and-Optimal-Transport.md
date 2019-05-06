---
layout: post
title: "Neural Architecture Search with Bayesian Optimisation and Optimal Transport"
date: 2019-03-15 18:23:39
categories: arXiv_CV
tags: arXiv_CV NAS CNN Deep_Learning
author: Kirthevasan Kandasamy, Willie Neiswanger, Jeff Schneider, Barnabas Poczos, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian Optimisation (BO) refers to a class of methods for global optimisation of a function $f$ which is only accessible via point evaluations. It is typically used in settings where $f$ is expensive to evaluate. A common use case for BO in machine learning is model selection, where it is not possible to analytically model the generalisation performance of a statistical model, and we resort to noisy and expensive training and validation procedures to choose the best model. Conventional BO methods have focused on Euclidean and categorical domains, which, in the context of model selection, only permits tuning scalar hyper-parameters of machine learning algorithms. However, with the surge of interest in deep learning, there is an increasing demand to tune neural network \emph{architectures}. In this work, we develop NASBOT, a Gaussian process based BO framework for neural architecture search. To accomplish this, we develop a distance metric in the space of neural network architectures which can be computed efficiently via an optimal transport program. This distance might be of independent interest to the deep learning community as it may find applications outside of BO. We demonstrate that NASBOT outperforms other alternatives for architecture search in several cross validation based model selection tasks on multi-layer perceptrons and convolutional neural networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.07191](https://arxiv.org/abs/1802.07191)

##### PDF
[https://arxiv.org/pdf/1802.07191](https://arxiv.org/pdf/1802.07191)

