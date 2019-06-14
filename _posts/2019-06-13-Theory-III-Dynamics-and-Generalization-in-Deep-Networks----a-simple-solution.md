---
layout: post
title: "Theory III: Dynamics and Generalization in Deep Networks -- a simple solution"
date: 2019-06-13 02:02:40
categories: arXiv_AI
tags: arXiv_AI Classification Gradient_Descent Relation
author: Andrzej Banburski, Qianli Liao, Brando Miranda, Lorenzo Rosasco, Jack Hidary, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
Classical generalization bounds for classification in the setting of separable data can be optimized by maximizing the margin of a deep network under the constraint of unit p-norm of the weight matrix at each layer. A possible approach for solving numerically this problem uses gradient algorithms on exponential-type loss functions, enforcing a unit constraint in the p-norm. In the limiting case of continuous gradient flow, we analyze the dynamical systems associated with three algorithms of this kind and their close relation for $p=2$ with existing weight normalization and batch normalization algorithms. An interesting observation is that unconstrained gradient descent has a similar dynamics with the same critical points and thus also optimizes the generalization bounds. Our approach extends some of the results of Srebro from linear networks to deep networks and provides a new perspective on the implicit bias of gradient descent. This elusive complexity control is likely to be responsible for generalization despite overparametrization in deep networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04991](http://arxiv.org/abs/1903.04991)

##### PDF
[http://arxiv.org/pdf/1903.04991](http://arxiv.org/pdf/1903.04991)

