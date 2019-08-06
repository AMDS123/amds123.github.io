---
layout: post
title: "SqueezeNAS: Fast neural architecture search for faster semantic segmentation"
date: 2019-08-05 17:46:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Semantic_Segmentation Inference Classification
author: Albert Shaw, Daniel Hunter, Forrest Iandola, Sammy Sidhu
mathjax: true
---

* content
{:toc}

##### Abstract
For real time applications utilizing Deep Neural Networks (DNNs), it is critical that the models achieve high-accuracy on the target task and low-latency inference on the target computing platform. While Neural Architecture Search (NAS) has been effectively used to develop low-latency networks for image classification, there has been relatively little effort to use NAS to optimize DNN architectures for other vision tasks. In this work, we present what we believe to be the first proxyless hardware-aware search targeted for dense semantic segmentation. With this approach, we advance the state-of-the-art accuracy for latency-optimized networks on the Cityscapes semantic segmentation dataset. Our latency-optimized small SqueezeNAS network achieves 68.02% validation class mIOU with less than 35 ms inference times on the NVIDIA AGX Xavier. Our latency-optimized large SqueezeNAS network achieves 73.62% class mIOU with less than 100 ms inference times. We demonstrate that significant performance gains are possible by utilizing NAS to find networks optimized for both the specific task and inference hardware. We also present detailed analysis comparing our networks to recent state-of-the-art architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01748](http://arxiv.org/abs/1908.01748)

##### PDF
[http://arxiv.org/pdf/1908.01748](http://arxiv.org/pdf/1908.01748)

