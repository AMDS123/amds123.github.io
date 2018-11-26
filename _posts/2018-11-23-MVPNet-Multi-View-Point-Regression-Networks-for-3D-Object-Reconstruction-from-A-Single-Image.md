---
layout: post
title: "MVPNet: Multi-View Point Regression Networks for 3D Object Reconstruction from A Single Image"
date: 2018-11-23 09:56:48
categories: arXiv_CV
tags: arXiv_CV Face
author: Jinglu Wang, Bo Sun, Yan Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of reconstructing an object's surface from a single image using generative networks. First, we represent a 3D surface with an aggregation of dense point clouds from multiple views. Each point cloud is embedded in a regular 2D grid aligned on an image plane of a viewpoint, making the point cloud convolution-favored and ordered so as to fit into deep network architectures. The point clouds can be easily triangulated by exploiting connectivities of the 2D grids to form mesh-based surfaces. Second, we propose an encoder-decoder network that generates such kind of multiple view-dependent point clouds from a single image by regressing their 3D coordinates and visibilities. We also introduce a novel geometric loss that is able to interpret discrepancy over 3D surfaces as opposed to 2D projective planes, resorting to the surface discretization on the constructed meshes. We demonstrate that the multi-view point regression network outperforms state-of-the-art methods with a significant improvement on challenging datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09410](http://arxiv.org/abs/1811.09410)

##### PDF
[http://arxiv.org/pdf/1811.09410](http://arxiv.org/pdf/1811.09410)

