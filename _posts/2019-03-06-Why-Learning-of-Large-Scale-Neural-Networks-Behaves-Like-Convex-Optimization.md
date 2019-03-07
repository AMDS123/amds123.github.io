---
layout: post
title: "Why Learning of Large-Scale Neural Networks Behaves Like Convex Optimization"
date: 2019-03-06 02:21:37
categories: arXiv_AI
tags: arXiv_AI Optimization Gradient_Descent
author: Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present some theoretical work to explain why simple gradient descent methods are so successful in solving non-convex optimization problems in learning large-scale neural networks (NN). After introducing a mathematical tool called canonical space, we have proved that the objective functions in learning NNs are convex in the canonical model space. We further elucidate that the gradients between the original NN model space and the canonical space are related by a pointwise linear transformation, which is represented by the so-called disparity matrix. Furthermore, we have proved that gradient descent methods surely converge to a global minimum of zero loss provided that the disparity matrices maintain full rank. If this full-rank condition holds, the learning of NNs behaves in the same way as normal convex optimization. At last, we have shown that the chance to have singular disparity matrices is extremely slim in large NNs. In particular, when over-parameterized NNs are randomly initialized, the gradient decent algorithms converge to a global minimum of zero loss in probability.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02140](http://arxiv.org/abs/1903.02140)

##### PDF
[http://arxiv.org/pdf/1903.02140](http://arxiv.org/pdf/1903.02140)

