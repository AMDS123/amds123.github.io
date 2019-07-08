---
layout: post
title: "A Spectral Approach to Unsupervised Object Segmentation in Video"
date: 2019-07-05 09:07:19
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Relation
author: Elena Burceanu, Marius Leordeanu
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate object segmentation in video as a graph partitioning problem in both space and time, in which nodes are pixels and their relations form local neighbourhoods. We claim that the strongest cluster in this pixel level graph represents the salient object segmentation. We compute the main cluster using a novel and fast 3D filtering technique that finds the spectral clustering solution, namely the principal eigenvector of the graph's adjacency matrix, without building the matrix explicitly - which would be intractable. Our method is based on the power iteration for finding the principal eigenvector of a matrix, which we prove that it is equivalent to performing a specific set of 3D convolutions in the space-time feature volume. This allows us to avoid creating the matrix and have a fast parallel implementation on GPU. We show that our approach is also suitable for online processing of video streams, while being much faster than the classical power iteration applied directly on the adjacency matrix. Different from other works, our approach is dedicated to preserving object consistency in space and time at the level of pixels. For that it requires powerful pixel-wise features at the frame level. This makes it perfectly suitable for using as features the output of existing segmentation algorithms and fast improving over their solution, without any other supervision. In experiments, we obtain consistent improvement, using the same set of hyper-parameters, over the top state of the art methods on DAVIS-2016 dataset, both in unsupervised and semi-supervised tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02731](http://arxiv.org/abs/1907.02731)

##### PDF
[http://arxiv.org/pdf/1907.02731](http://arxiv.org/pdf/1907.02731)

