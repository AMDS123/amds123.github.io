---
layout: post
title: "Fast Deep Stereo with 2D Convolutional Processing of Cost Signatures"
date: 2019-03-08 16:39:28
categories: arXiv_CV
tags: arXiv_CV CNN
author: Kyle Yee, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural network-based algorithms are able to produce highly accurate depth estimates from stereo image pairs, nearly matching the reliability of measurements from more expensive depth sensors. However, this accuracy comes with a higher computational cost since these methods use network architectures designed to compute and process matching scores across all candidate matches at all locations, with floating point computations repeated across a match volume with dimensions corresponding to both space and disparity. This leads to longer running times to process each image pair, making them impractical for real-time use in robots and autonomous vehicles. We propose a new stereo algorithm that employs a significantly more efficient network architecture. Our method builds an initial match cost volume using traditional matching costs that are fast to compute, and trains a network to estimate disparity from this volume. Crucially, our network only employs per-pixel and two-dimensional convolution operations: to summarize the match information at each location as a low-dimensional feature vector, and to spatially process these `cost-signature' features to produce a dense disparity map. Experimental results on the KITTI benchmark show that our method delivers competitive accuracy at significantly higher speeds---running at 48 frames per second on a modern GPU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04939](http://arxiv.org/abs/1903.04939)

##### PDF
[http://arxiv.org/pdf/1903.04939](http://arxiv.org/pdf/1903.04939)

