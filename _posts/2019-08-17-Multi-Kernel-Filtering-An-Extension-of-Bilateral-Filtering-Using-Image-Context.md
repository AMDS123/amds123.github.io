---
layout: post
title: "Multi-Kernel Filtering: An Extension of Bilateral Filtering Using Image Context"
date: 2019-08-17 14:43:00
categories: arXiv_CV
tags: arXiv_CV GAN
author: Feihong Liu, Jun Feng, Pew-Thian Yap, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Bilateral filtering is one of the most classical denoising filters. However, the parameter of its range kernel needs to be initialized manually, which hampers its adaptivity across images with different characteristics. For coping with image variation (e.g., changeable signal-to-noise ratio and spatially-varying noise), it is necessary to adapt the kernel to specific image characteristics automatically. In this paper, we propose multi-kernel filter (MKF) inspired by adaptive mechanisms of human vision. We first design a hierarchically clustering algorithm to generate a hierarchy of large to small coherent image patches, organized as a cluster tree, so that multi-scale represent an image. One leaf cluster and two corresponding predecessor clusters are used to generate one of a number of range kernels that are capable of catering to image variation. We evaluate MKF on two public datasets, BSD$300$ and Phantom$\alpha$s. Extensive experimental results show that MKF outperforms various state-of-the-art filters on both mean absolute error and structural similarity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06307](http://arxiv.org/abs/1908.06307)

##### PDF
[http://arxiv.org/pdf/1908.06307](http://arxiv.org/pdf/1908.06307)

