---
layout: post
title: "Graph HyperNetworks for Neural Architecture Search"
date: 2018-10-12 22:21:05
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Chris Zhang, Mengye Ren, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search (NAS) automatically finds the best task-specific neural network topology, outperforming many manual architecture designs. However, it can be prohibitively expensive as the search requires training thousands of different networks, while each can last for hours. In this work, we propose the Graph HyperNetwork (GHN) to amortize the search cost: given an architecture, it directly generates the weights by running inference on a graph neural network. GHNs model the topology of an architecture and therefore can predict network performance more accurately than regular hypernetworks and premature early stopping. To perform NAS, we randomly sample architectures and use the validation accuracy of networks with GHN generated weights as the surrogate search signal. GHNs are fast -- they can search nearly 10 times faster than other random search methods on CIFAR-10 and ImageNet. GHNs can be further extended to the anytime prediction setting, where they have found networks with better speed-accuracy tradeoff than the state-of-the-art manual designs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05749](https://arxiv.org/abs/1810.05749)

##### PDF
[https://arxiv.org/pdf/1810.05749](https://arxiv.org/pdf/1810.05749)

