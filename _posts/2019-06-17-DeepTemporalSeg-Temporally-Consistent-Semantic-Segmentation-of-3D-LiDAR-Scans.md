---
layout: post
title: "DeepTemporalSeg: Temporally Consistent Semantic Segmentation of 3D LiDAR Scans"
date: 2019-06-17 11:35:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Tracking CNN Semantic_Segmentation Prediction
author: Ayush Dewan, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the semantic characteristics of the environment is a key enabler for autonomous robot operation. In this paper, we propose a deep convolutional neural network (DCNN) for the semantic segmentation of a LiDAR scan into the classes car, pedestrian or bicyclist. This architecture is based on dense blocks and efficiently utilizes depth separable convolutions to limit the number of parameters while still maintaining state-of-the-art performance. To make the predictions from the DCNN temporally consistent, we propose a Bayes filter based method. This method uses the predictions from the neural network to recursively estimate the current semantic state of a point in a scan. This recursive estimation uses the knowledge gained from previous scans, thereby making the predictions temporally consistent and robust towards isolated erroneous predictions. We compare the performance of our proposed architecture with other state-of-the-art neural network architectures and report substantial improvement. For the proposed Bayes filter approach, we show results on various sequences in the KITTI tracking benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06962](http://arxiv.org/abs/1906.06962)

##### PDF
[http://arxiv.org/pdf/1906.06962](http://arxiv.org/pdf/1906.06962)

