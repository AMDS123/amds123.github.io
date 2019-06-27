---
layout: post
title: "Spatial Transformer for 3D Points"
date: 2019-06-26 07:41:13
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jiayun Wang, Rudrasis Chakraborty, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Point cloud is an efficient representation of 3D visual data, and enables deep neural networks to effectively understand and model the 3D visual world. All the previous methods used the same original point cloud location at different layers of the network to define "local patches". Depending on the neighborhood of the local patches, they learn the local feature and finally form a feature map. Though this is easy to do but not necessarily optimal. As with different layers the "local patches" structure will also change. Thus, one needs to learn the transformation of the original point cloud in each layer, and learn the feature maps from the "local patches" on the transformed coordinates. In this work, we propose a novel approach to learn non-rigid transformation of input point clouds in each layer. We propose both linear (affine) and non-linear (projective, deformable) spatial transformer on 3D point cloud and our proposed method outperforms the state-of-the-art fixed point counterparts in benchmark point cloud segmentation datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10887](http://arxiv.org/abs/1906.10887)

##### PDF
[http://arxiv.org/pdf/1906.10887](http://arxiv.org/pdf/1906.10887)

