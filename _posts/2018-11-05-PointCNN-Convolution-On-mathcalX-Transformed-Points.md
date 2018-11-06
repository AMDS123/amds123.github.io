---
layout: post
title: "PointCNN: Convolution On $mathcal{X}$-Transformed Points"
date: 2018-11-05 09:31:45
categories: arXiv_AI
tags: arXiv_AI Relation
author: Yangyan Li, Rui Bu, Mingchao Sun, Wei Wu, Xinhan Di, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and general framework for feature learning from point clouds. The key to the success of CNNs is the convolution operator that is capable of leveraging spatially-local correlation in data represented densely in grids (e.g. images). However, point clouds are irregular and unordered, thus directly convolving kernels against features associated with the points, will result in desertion of shape information and variance to point ordering. To address these problems, we propose to learn an $\mathcal{X}$-transformation from the input points, to simultaneously promote two causes. The first is the weighting of the input features associated with the points, and the second is the permutation of the points into a latent and potentially canonical order. Element-wise product and sum operations of the typical convolution operator are subsequently applied on the $\mathcal{X}$-transformed features. The proposed method is a generalization of typical CNNs to feature learning from point clouds, thus we call it PointCNN. Experiments show that PointCNN achieves on par or better performance than state-of-the-art methods on multiple challenging benchmark datasets and tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.07791](http://arxiv.org/abs/1801.07791)

##### PDF
[http://arxiv.org/pdf/1801.07791](http://arxiv.org/pdf/1801.07791)

