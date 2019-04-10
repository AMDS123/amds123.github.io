---
layout: post
title: "3D Point Cloud Denoising via Deep Neural Network based Local Surface Estimation"
date: 2019-04-09 02:29:39
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Deep_Learning
author: Chaojing Duan, Siheng Chen, Jelena Kovacevic
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural-network-based architecture for 3D point cloud denoising called neural projection denoising (NPD). In our previous work, we proposed a two-stage denoising algorithm, which first estimates reference planes and follows by projecting noisy points to estimated reference planes. Since the estimated reference planes are inevitably noisy, multi-projection is applied to stabilize the denoising performance. NPD algorithm uses a neural network to estimate reference planes for points in noisy point clouds. With more accurate estimations of reference planes, we are able to achieve better denoising performances with only one-time projection. To the best of our knowledge, NPD is the first work to denoise 3D point clouds with deep learning techniques. To conduct the experiments, we sample 40000 point clouds from the 3D data in ShapeNet to train a network and sample 350 point clouds from the 3D data in ModelNet10 to test. Experimental results show that our algorithm can estimate normal vectors of points in noisy point clouds. Comparing to five competitive methods, the proposed algorithm achieves better denoising performance and produces much smaller variances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04427](http://arxiv.org/abs/1904.04427)

##### PDF
[http://arxiv.org/pdf/1904.04427](http://arxiv.org/pdf/1904.04427)

