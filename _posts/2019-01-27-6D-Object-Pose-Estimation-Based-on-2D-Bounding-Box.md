---
layout: post
title: "6D Object Pose Estimation Based on 2D Bounding Box"
date: 2019-01-27 12:40:04
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Jin Liu, Sheng He
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a simple but powerful method to tackle the problem of estimating the 6D pose of objects from a single RGB image. Our system trains a novel convolutional neural network to regress the unit quaternion, which represents the 3D rotation, from the partial image inside the bounding box returned by 2D detection systems. Then we propose an algorithm we call Bounding Box Equation to efficiently and accurately obtain the 3D translation, using 3D rotation and 2D bounding box. Considering that the quadratic sum of the quaternion's four elements equals to one, we add a normalization layer to keep the network's output on the unit sphere and put forward a special loss function for unit quaternion regression. We evaluate our method on the LineMod dataset and experiment shows that our approach outperforms base-line and some state of the art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09366](http://arxiv.org/abs/1901.09366)

##### PDF
[http://arxiv.org/pdf/1901.09366](http://arxiv.org/pdf/1901.09366)

