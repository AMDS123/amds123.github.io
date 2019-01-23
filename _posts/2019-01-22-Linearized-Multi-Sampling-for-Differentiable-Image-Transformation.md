---
layout: post
title: "Linearized Multi-Sampling for Differentiable Image Transformation"
date: 2019-01-22 00:07:12
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning
author: Wei Jiang, Weiwei Sun, Andrea Tagliasacchi, Eduard Trulls, Kwang Moo Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel image sampling method for differentiable image transformation in deep neural networks. The sampling schemes currently used in deep learning, such as Spatial Transformer Networks, rely on bilinear interpolation, which performs poorly under severe scale changes, and more importantly, results in poor gradient propagation. This is due to their strict reliance on direct neighbors. Instead, we propose to generate random auxiliary samples in the vicinity of each pixel in the sampled image, and create a linear approximation using their intensity values. We then use this approximation as a differentiable formula for the transformed image. However, we observe that these auxiliary samples may collapse to a single pixel under severe image transformations, and propose to address it by adding constraints to the distance between the center pixel and the auxiliary samples. We demonstrate that our approach produces more representative gradients with a wider basin of convergence for image alignment, which leads to considerable performance improvements when training networks for image registration and classification tasks, particularly under large downsampling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07124](http://arxiv.org/abs/1901.07124)

##### PDF
[http://arxiv.org/pdf/1901.07124](http://arxiv.org/pdf/1901.07124)

