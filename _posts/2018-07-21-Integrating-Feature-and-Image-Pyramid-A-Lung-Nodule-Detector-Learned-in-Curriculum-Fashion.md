---
layout: post
title: "Integrating Feature and Image Pyramid: A Lung Nodule Detector Learned in Curriculum Fashion"
date: 2018-07-21 12:02:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Benyuan Sun, Zhen Zhou, Fandong Zhang, Xiuli Li, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Lung nodules suffer large variation in size and appearance in CT images. Nodules less than 10mm can easily lose information after down-sampling in convolutional neural networks, which results in low sensitivity. In this paper, a combination of 3D image and feature pyramid is exploited to integrate lower-level texture features with high-level semantic features, thus leading to a higher recall. However, 3D operations are time and memory consuming, which aggravates the situation with the explosive growth of medical images. To tackle this problem, we propose a general curriculum training strategy to speed up training. An dynamic sampling method is designed to pick up partial samples which give the best contribution to network training, thus leading to much less time consuming. In experiments, we demonstrate that the proposed network outperforms previous state-of-the-art methods. Meanwhile, our sampling strategy halves the training time of the proposal network on LUNA16.

##### Abstract (translated by Google)
肺结节在CT图像中的大小和外观上有很大的变化。在卷积神经网络中下采样后，小于10mm的结节很容易丢失信息，导致灵敏度低。在本文中，利用3D图像和特征金字塔的组合将较低级别的纹理特征与高级语义特征相结合，从而导致更高的召回率。然而，3D操作耗费时间和记忆，这加剧了医学图像爆炸性增长的情况。为解决这个问题，我们提出了一般的课程培训策略，以加快培训。动态采样方法旨在获取对网络训练有最大贡献的部分样本，从而减少耗时。在实验中，我们证明了所提出的网络优于以前最先进的方法。同时，我们的抽样策略将LUNA16上的提案网络的培训时间缩短了一半。

##### URL
[http://arxiv.org/abs/1807.08135](http://arxiv.org/abs/1807.08135)

##### PDF
[http://arxiv.org/pdf/1807.08135](http://arxiv.org/pdf/1807.08135)

