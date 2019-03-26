---
layout: post
title: "Capsule Networks with Max-Min Normalization"
date: 2019-03-22 18:09:37
categories: arXiv_CV
tags: arXiv_CV
author: Zhen Zhao, Ashley Kleinhans, Gursharan Sandhu, Ishan Patel, K. P. Unnikrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
Capsule Networks (CapsNet) use the Softmax function to convert the logits of the routing coefficients into a set of normalized values that signify the assignment probabilities between capsules in adjacent layers. We show that the use of Softmax prevents capsule layers from forming optimal couplings between lower and higher-level capsules. Softmax constrains the dynamic range of the routing coefficients and leads to probabilities that remain mostly uniform after several routing iterations. Instead, we propose the use of Max-Min normalization. Max-Min performs a scale-invariant normalization of the logits that allows each lower-level capsule to take on an independent value, constrained only by the bounds of normalization. Max-Min provides consistent improvement in test accuracy across five datasets and allows more routing iterations without a decrease in network performance. A single CapsNet trained using Max-Min achieves an improved test error of 0.20% on the MNIST dataset. With a simple 3-model majority vote, we achieve a test error of 0.17% on MNIST.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09662](http://arxiv.org/abs/1903.09662)

##### PDF
[http://arxiv.org/pdf/1903.09662](http://arxiv.org/pdf/1903.09662)

