---
layout: post
title: "Learning Guided Convolutional Network for Depth Completion"
date: 2019-08-03 22:06:34
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Jie Tang, Fei-Peng Tian, Wei Feng, Jian Li, Ping Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Dense depth perception is critical for autonomous driving and other robotics applications. However, modern LiDAR sensors only provide sparse depth measurement. It is thus necessary to complete the sparse LiDAR data, where a synchronized guidance RGB image is often used to facilitate this completion. Many neural networks have been designed for this task. However, they often na\"{\i}vely fuse the LiDAR data and RGB image information by performing feature concatenation or element-wise addition. Inspired by the guided image filtering, we design a novel guided network to predict kernel weights from the guidance image. These predicted kernels are then applied to extract the depth image features. In this way, our network generates content-dependent and spatially-variant kernels for multi-modal feature fusion. Dynamically generated spatially-variant kernels could lead to prohibitive GPU memory consumption and computation overhead. We further design a convolution factorization to reduce computation and memory consumption. The GPU memory reduction makes it possible for feature fusion to work in multi-stage scheme. We conduct comprehensive experiments to verify our method on real-world outdoor, indoor and synthetic datasets. Our method produces strong results. It outperforms state-of-the-art methods on the NYUv2 dataset and ranks 1st on the KITTI depth completion benchmark at the time of submission. It also presents strong generalization capability under different 3D point densities, various lighting and weather conditions as well as cross-dataset evaluations. The code will be released for reproduction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01238](http://arxiv.org/abs/1908.01238)

##### PDF
[http://arxiv.org/pdf/1908.01238](http://arxiv.org/pdf/1908.01238)

