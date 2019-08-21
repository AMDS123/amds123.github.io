---
layout: post
title: "BoxNet: A Deep Learning Method for 2D Bounding Box Estimation from Bird's-Eye View Point Cloud"
date: 2019-08-19 21:50:41
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Ehsan Nezhadarya, Yang Liu, Bingbing Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning-based method to estimate the object bounding box from its 2D bird's-eye view (BEV) LiDAR points. Our method, entitled BoxNet, exploits a simple deep neural network that can efficiently handle unordered points. The method takes as input the 2D coordinates of all the points and the output is a vector consisting of both the box pose (position and orientation in LiDAR coordinate system) and its size (width and length). In order to deal with the angle discontinuity problem, we propose to estimate the double-angle sinusoidal values rather than the angle itself. We also predict the center relative to the point cloud mean to boost the performance of estimating the location of the box. The proposed method does not rely on the ordering of points as in many existing approaches, and can accurately predict the actual size of the bounding box based on the prior information that is obtained from the training data. BoxNet is validated using the KITTI 3D object dataset, with significant improvement compared with the state-of-the-art non-learning based methods

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07085](http://arxiv.org/abs/1908.07085)

##### PDF
[http://arxiv.org/pdf/1908.07085](http://arxiv.org/pdf/1908.07085)

