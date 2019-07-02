---
layout: post
title: "Dissecting Pruned Neural Networks"
date: 2019-06-29 19:27:57
categories: arXiv_CV
tags: arXiv_CV Relation
author: Jonathan Frankle, David Bau
mathjax: true
---

* content
{:toc}

##### Abstract
Pruning is a standard technique for removing unnecessary structure from a neural network to reduce its storage footprint, computational demands, or energy consumption. Pruning can reduce the parameter-counts of many state-of-the-art neural networks by an order of magnitude without compromising accuracy, meaning these networks contain a vast amount of unnecessary structure. In this paper, we study the relationship between pruning and interpretability. Namely, we consider the effect of removing unnecessary structure on the number of hidden units that learn disentangled representations of human-recognizable concepts as identified by network dissection. We aim to evaluate how the interpretability of pruned neural networks changes as they are compressed. We find that pruning has no detrimental effect on this measure of interpretability until so few parameters remain that accuracy beings to drop. Resnet-50 models trained on ImageNet maintain the same number of interpretable concepts and units until more than 90% of parameters have been pruned.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00262](http://arxiv.org/abs/1907.00262)

##### PDF
[http://arxiv.org/pdf/1907.00262](http://arxiv.org/pdf/1907.00262)

