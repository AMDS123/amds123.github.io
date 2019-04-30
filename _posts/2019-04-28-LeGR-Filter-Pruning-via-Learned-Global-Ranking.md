---
layout: post
title: "LeGR: Filter Pruning via Learned Global Ranking"
date: 2019-04-28 18:51:26
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Ting-Wu Chin, Ruizhou Ding, Cha Zhang, Diana Marculescu
mathjax: true
---

* content
{:toc}

##### Abstract
Filter pruning has shown to be effective for learning resource-constrained convolutional neural networks (CNNs). However, prior methods for resource-constrained filter pruning have some limitations that hinder their effectiveness and efficiency. When searching for constraint-satisfying CNNs, prior methods either alter the optimization objective or adopt local search algorithms with heuristic parameterization, which are sub-optimal, especially in low-resource regime. From the efficiency perspective, prior methods are often costly to search for constraint-satisfying CNNs. In this work, we propose learned global ranking, dubbed LeGR, which improves upon prior art in the two aforementioned dimensions. Inspired by theoretical analysis, LeGR is parameterized to learn layer-wise affine transformations over the filter norms to construct a learned global ranking. With global ranking, resource-constrained filter pruning at various constraint levels can be done efficiently. We conduct extensive empirical analyses to demonstrate the effectiveness of the proposed algorithm with ResNet and MobileNetV2 networks on CIFAR-10, CIFAR-100, Bird-200, and ImageNet datasets. Code is publicly available at https://github.com/cmu-enyac/LeGR.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12368](http://arxiv.org/abs/1904.12368)

##### PDF
[http://arxiv.org/pdf/1904.12368](http://arxiv.org/pdf/1904.12368)

