---
layout: post
title: "Robust Attentional Aggregation of Deep Feature Sets for Multi-view 3D Reconstruction"
date: 2019-08-18 06:32:40
categories: arXiv_AI
tags: arXiv_AI Attention
author: Bo Yang, Sen Wang, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of recovering an underlying 3D shape from a set of images. Existing learning based approaches usually resort to recurrent neural nets, e.g., GRU, or intuitive pooling operations, e.g., max/mean poolings, to fuse multiple deep features encoded from input images. However, GRU based approaches are unable to consistently estimate 3D shapes given different permutations of the same set of input images as the recurrent unit is permutation variant. It is also unlikely to refine the 3D shape given more images due to the long-term memory loss of GRU. Commonly used pooling approaches are limited to capturing partial information, e.g., max/mean values, ignoring other valuable features. In this paper, we present a new feed-forward neural module, named AttSets, together with a dedicated training algorithm, named FASet, to attentively aggregate an arbitrarily sized deep feature set for multi-view 3D reconstruction. The AttSets module is permutation invariant, computationally efficient and flexible to implement, while the FASet algorithm enables the AttSets based network to be remarkably robust and generalize to an arbitrary number of input images. We thoroughly evaluate FASet and the properties of AttSets on multiple large public datasets. Extensive experiments show that AttSets together with FASet algorithm significantly outperforms existing aggregation approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.00758](http://arxiv.org/abs/1808.00758)

##### PDF
[http://arxiv.org/pdf/1808.00758](http://arxiv.org/pdf/1808.00758)

