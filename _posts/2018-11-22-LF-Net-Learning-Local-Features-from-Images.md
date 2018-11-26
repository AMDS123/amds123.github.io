---
layout: post
title: "LF-Net: Learning Local Features from Images"
date: 2018-11-22 11:10:42
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Yuki Ono, Eduard Trulls, Pascal Fua, Kwang Moo Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deep architecture and a training strategy to learn a local feature pipeline from scratch, using collections of images without the need for human supervision. To do so we exploit depth and relative camera pose cues to create a virtual target that the network should achieve on one image, provided the outputs of the network for the other image. While this process is inherently non-differentiable, we show that we can optimize the network in a two-branch setup by confining it to one branch, while preserving differentiability in the other. We train our method on both indoor and outdoor datasets, with depth data from 3D sensors for the former, and depth estimates from an off-the-shelf Structure-from-Motion solution for the latter. Our models outperform the state of the art on sparse feature matching on both datasets, while running at 60+ fps for QVGA images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09662](http://arxiv.org/abs/1805.09662)

##### PDF
[http://arxiv.org/pdf/1805.09662](http://arxiv.org/pdf/1805.09662)

