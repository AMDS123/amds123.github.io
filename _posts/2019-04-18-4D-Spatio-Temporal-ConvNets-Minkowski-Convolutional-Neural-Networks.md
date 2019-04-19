---
layout: post
title: "4D Spatio-Temporal ConvNets: Minkowski Convolutional Neural Networks"
date: 2019-04-18 13:19:50
categories: arXiv_AI
tags: arXiv_AI Sparse Segmentation CNN Semantic_Segmentation
author: Christopher Choy, JunYoung Gwak, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
In many robotics and VR/AR applications, 3D-videos are readily-available sources of input (a continuous sequence of depth images, or LIDAR scans). However, those 3D-videos are processed frame-by-frame either through 2D convnets or 3D perception algorithms. In this work, we propose 4-dimensional convolutional neural networks for spatio-temporal perception that can directly process such 3D-videos using high-dimensional convolutions. For this, we adopt sparse tensors and propose the generalized sparse convolution that encompasses all discrete convolutions. To implement the generalized sparse convolution, we create an open-source auto-differentiation library for sparse tensors that provides extensive functions for high-dimensional convolutional neural networks. We create 4D spatio-temporal convolutional neural networks using the library and validate them on various 3D semantic segmentation benchmarks and proposed 4D datasets for 3D-video perception. To overcome challenges in the 4D space, we propose the hybrid kernel, a special case of the generalized sparse convolution, and the trilateral-stationary conditional random field that enforces spatio-temporal consistency in the 7D space-time-chroma space. Experimentally, we show that convolutional neural networks with only generalized 3D sparse convolutions can outperform 2D or 2D-3D hybrid methods by a large margin. Also, we show that on 3D-videos, 4D spatio-temporal convolutional neural networks are robust to noise, outperform 3D convolutional neural networks and are faster than the 3D counterpart in some cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08755](http://arxiv.org/abs/1904.08755)

##### PDF
[http://arxiv.org/pdf/1904.08755](http://arxiv.org/pdf/1904.08755)

