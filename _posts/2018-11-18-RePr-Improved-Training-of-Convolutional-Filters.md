---
layout: post
title: "RePr: Improved Training of Convolutional Filters"
date: 2018-11-18 05:15:27
categories: arXiv_CV
tags: arXiv_CV CNN
author: Aaditya Prakash, James Storer, Dinei Florencio, Cha Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
A well-trained Convolutional Neural Network can easily be pruned without significant loss of performance. This is because of unnecessary overlap in the features captured by the network's filters. Innovations in network architecture such as skip/dense connections and Inception units have mitigated this problem to some extent, but these improvements come with increased computation and memory requirements at run-time. We attempt to address this problem from another angle - not by changing the network structure but by altering the training method. We show that by temporarily pruning and then restoring a subset of the model's filters, and repeating this process cyclically, overlap in the learned features is reduced, producing improved generalization. We show that the existing model-pruning criteria are not optimal for selecting filters to prune in this context and introduce inter-filter orthogonality as the ranking criteria to determine under-expressive filters. Our method is applicable both to vanilla convolutional networks and more complex modern architectures, and improves the performance across a variety of tasks, especially when applied to smaller networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07275](http://arxiv.org/abs/1811.07275)

##### PDF
[http://arxiv.org/pdf/1811.07275](http://arxiv.org/pdf/1811.07275)

