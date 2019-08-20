---
layout: post
title: "Conv2Warp: An unsupervised deformable image registration with continuous convolution and warping"
date: 2019-08-16 22:21:07
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Sharib Ali, Jens Rittscher
mathjax: true
---

* content
{:toc}

##### Abstract
Recent successes in deep learning based deformable image registration (DIR) methods have demonstrated that complex deformation can be learnt directly from data while reducing computation time when compared to traditional methods. However, the reliance on fully linear convolutional layers imposes a uniform sampling of pixel/voxel locations which ultimately limits their performance. To address this problem, we propose a novel approach of learning a continuous warp of the source image. Here, the required deformation vector fields are obtained from a concatenated linear and non-linear convolution layers and a learnable bicubic Catmull-Rom spline resampler. This allows to compute smooth deformation field and more accurate alignment compared to using only linear convolutions and linear resampling. In addition, the continuous warping technique penalizes disagreements that are due to topological changes. Our experiments demonstrate that this approach manages to capture large non-linear deformations and minimizes the propagation of interpolation errors. While improving accuracy the method is computationally efficient. We present comparative results on a range of public 4D CT lung (POPI) and brain datasets (CUMC12, MGH10).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06194](http://arxiv.org/abs/1908.06194)

##### PDF
[http://arxiv.org/pdf/1908.06194](http://arxiv.org/pdf/1908.06194)

