---
layout: post
title: "Building Deep, Equivariant Capsule Networks"
date: 2019-08-04 09:14:29
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Sairaam Venkatraman, S. Balasubramanian, R. Raghunatha Sarma
mathjax: true
---

* content
{:toc}

##### Abstract
Capsule networks are constrained by their, relative, inability to deeper in a parameter-inexpensive manner, and also by the general lack of equivariance guarantees. As a step towards bridging these two gaps, we present a new variation of capsule networks termed Space-of-Variation networks (SOVNET). Each layer in SOVNET learns to projectively represent the manifold of legal pose variations for a set of capsules, using learnable neural network - one per capsule-type. Thus, shallower capsules from a local pool predict a deeper capsule by being input into the neural network associated with the type of deeper capsule. In order to capture local object-structures better, benefit from increased parameter-sharing, and have equivariance guarantees; group-equivariant convolutions are used in the prediction mechanism. Further, a new routing algorithm based on the degree-centrality of graph nodes is presented. Experiments on affinely transformed versions of MNIST and FashionMNIST showcase the superiority of SOVNET over certain capsule-network baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01300](http://arxiv.org/abs/1908.01300)

##### PDF
[http://arxiv.org/pdf/1908.01300](http://arxiv.org/pdf/1908.01300)

