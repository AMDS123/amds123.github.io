---
layout: post
title: "Adaptive Hierarchical Down-Sampling for Point Cloud Classification"
date: 2019-04-11 23:10:13
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Ehsan Nezhadarya, Ehsan Taghavi, Bingbing Liu, Jun Luo
mathjax: true
---

* content
{:toc}

##### Abstract
While several convolution-like operators have recently been proposed for extracting features out of point clouds, down-sampling an unordered point cloud in a deep neural network has not been rigorously studied. Existing methods down-sample the points regardless of their importance for the output. As a result, some important points in the point cloud may be removed, while less valuable points may be passed to the next layers. In contrast, adaptive down-sampling methods sample the points by taking into account the importance of each point, which varies based on the application, task and training data. In this paper, we propose a permutation-invariant learning-based adaptive down-sampling layer, called Critical Points Layer (CPL), which reduces the number of points in an unordered point cloud while retaining the important points. Unlike most graph-based point cloud down-sampling methods that use $k$-NN search algorithm to find the neighbouring points, CPL is a global down-sampling method, rendering it computationally very efficient. The proposed layer can be used along with any graph-based point cloud convolution layer to form a convolutional neural network, dubbed CP-Net in this paper. We introduce a CP-Net for $3$D object classification that achieves the best accuracy for the ModelNet$40$ dataset among point cloud-based methods, which validates the effectiveness of the CPL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08506](http://arxiv.org/abs/1904.08506)

##### PDF
[http://arxiv.org/pdf/1904.08506](http://arxiv.org/pdf/1904.08506)

