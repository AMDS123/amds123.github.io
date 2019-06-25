---
layout: post
title: "ESNet: An Efficient Symmetric Network for Real-time Semantic Segmentation"
date: 2019-06-24 10:05:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Yu Wang, Quan Zhou, Xiaofu Wu
mathjax: true
---

* content
{:toc}

##### Abstract
The recent years have witnessed great advances for semantic segmentation using deep convolutional neural networks (DCNNs). However, a large number of convolutional layers and feature channels lead to semantic segmentation as a computationally heavy task, which is disadvantage to the scenario with limited resources. In this paper, we design an efficient symmetric network, called (ESNet), to address this problem. The whole network has nearly symmetric architecture, which is mainly composed of a series of factorized convolution unit (FCU) and its parallel counterparts (PFCU). On one hand, the FCU adopts a widely-used 1D factorized convolution in residual layers. On the other hand, the parallel version employs a transform-split-transform-merge strategy in the designment of residual module, where the split branch adopts dilated convolutions with different rate to enlarge receptive field. Our model has nearly 1.6M parameters, and is able to be performed over 62 FPS on a single GTX 1080Ti GPU. The experiments demonstrate that our approach achieves state-of-the-art results in terms of speed and accuracy trade-off for real-time semantic segmentation on CityScapes dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09826](http://arxiv.org/abs/1906.09826)

##### PDF
[http://arxiv.org/pdf/1906.09826](http://arxiv.org/pdf/1906.09826)

