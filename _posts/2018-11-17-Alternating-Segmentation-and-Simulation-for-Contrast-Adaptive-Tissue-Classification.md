---
layout: post
title: "Alternating Segmentation and Simulation for Contrast Adaptive Tissue Classification"
date: 2018-11-17 03:28:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Dzung L. Pham, Snehashis Roy
mathjax: true
---

* content
{:toc}

##### Abstract
A key feature of magnetic resonance (MR) imaging is its ability to manipulate how the intrinsic tissue parameters of the anatomy ultimately contribute to the contrast properties of the final, acquired image. This flexibility, however, can lead to substantial challenges for segmentation algorithms, particularly supervised methods. These methods require atlases or training data, which are composed of MR image and labeled image pairs. In most cases, the training data are obtained with a fixed acquisition protocol, leading to suboptimal performance when an input data set that requires segmentation has differing contrast properties. This drawback is increasingly significant with the recent movement towards multi-center research studies involving multiple scanners and acquisition protocols. In this work, we propose a new framework for supervised segmentation approaches that is robust to contrast differences between the training MR image and the input image. Our approach uses a generative simulation model within the segmentation process to compensate for the contrast differences. We allow the contrast of the MR image in the training data to vary by simulating a new contrast from the corresponding label image. The model parameters are optimized by a cost function measuring the consistency between the input MR image and its simulation based on a current estimate of the segmentation labels. We provide a proof of concept of this approach by combining a supervised classifier with a simple simulation model, and apply the resulting algorithm to synthetic images and actual MR images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07087](http://arxiv.org/abs/1811.07087)

##### PDF
[http://arxiv.org/pdf/1811.07087](http://arxiv.org/pdf/1811.07087)

