---
layout: post
title: "Importance Estimation for Neural Network Pruning"
date: 2019-06-25 22:20:16
categories: arXiv_CV
tags: arXiv_CV Inference Relation
author: Pavlo Molchanov, Arun Mallya, Stephen Tyree, Iuri Frosio, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Structural pruning of neural network parameters reduces computation, energy, and memory transfer costs during inference. We propose a novel method that estimates the contribution of a neuron (filter) to the final loss and iteratively removes those with smaller scores. We describe two variations of our method using the first and second-order Taylor expansions to approximate a filter's contribution. Both methods scale consistently across any network layer without requiring per-layer sensitivity analysis and can be applied to any kind of layer, including skip connections. For modern networks trained on ImageNet, we measured experimentally a high (&gt;93%) correlation between the contribution computed by our methods and a reliable estimate of the true importance. Pruning with the proposed methods leads to an improvement over state-of-the-art in terms of accuracy, FLOPs, and parameter reduction. On ResNet-101, we achieve a 40% FLOPS reduction by removing 30% of the parameters, with a loss of 0.02% in the top-1 accuracy on ImageNet. Code is available at https://github.com/NVlabs/Taylor_pruning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10771](http://arxiv.org/abs/1906.10771)

##### PDF
[http://arxiv.org/pdf/1906.10771](http://arxiv.org/pdf/1906.10771)

