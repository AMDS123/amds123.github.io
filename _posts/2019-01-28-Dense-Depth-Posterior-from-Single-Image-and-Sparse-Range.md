---
layout: post
title: "Dense Depth Posterior from Single Image and Sparse Range"
date: 2019-01-28 23:26:07
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning
author: Yanchao Yang, Alex Wong, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep learning system to infer the posterior distribution of a dense depth map associated with an image, by exploiting sparse range measurements, for instance from a lidar. While the lidar may provide a depth value for a small percentage of the pixels, we exploit regularities reflected in the training set to complete the map so as to have a probability over depth for each pixel in the image. We exploit a Conditional Prior Network, that allows associating a probability to each depth value given an image, and combine it with a likelihood term that uses the sparse measurements. Optionally we can also exploit the availability of stereo during training, but in any case only require a single image and a sparse point cloud at run-time. We test our approach on both unsupervised and supervised depth completion using the KITTI benchmark, and improve the state-of-the-art in both.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10034](http://arxiv.org/abs/1901.10034)

##### PDF
[http://arxiv.org/pdf/1901.10034](http://arxiv.org/pdf/1901.10034)

