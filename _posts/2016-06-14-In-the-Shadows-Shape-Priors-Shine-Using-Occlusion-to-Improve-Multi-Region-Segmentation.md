---
layout: post
title: "In the Shadows, Shape Priors Shine: Using Occlusion to Improve Multi-Region Segmentation"
date: 2016-06-14 23:12:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning
author: Yuka Kihara, Matvey Soloviev, Tsuhan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new algorithm for multi-region segmentation of 2D images with objects that may partially occlude each other. Our algorithm is based on the observation hat human performance on this task is based both on prior knowledge about plausible shapes and taking into account the presence of occluding objects whose shape is already known - once an occluded region is identified, the shape prior can be used to guess the shape of the missing part. We capture the former aspect using a deep learning model of shape; for the latter, we simultaneously minimize the energy of all regions and consider only unoccluded pixels for data agreement. Existing algorithms incorporating object shape priors consider every object separately in turn and can't distinguish genuine deviation from the expected shape from parts missing due to occlusion. We show that our method significantly improves on the performance of a representative algorithm, as evaluated on both preprocessed natural and synthetic images. Furthermore, on the synthetic images, we recover the ground truth segmentation with good accuracy.

##### Abstract (translated by Google)
我们提出了一个新的算法多区域二维图像分割与对象可能部分相互遮蔽。我们的算法基于观察帽，人类在这个任务上的表现是基于既定的可信形状的知识，并考虑到形状已知的遮挡物体的存在 - 一旦识别出遮挡区域，就可以使用先前的形状猜测缺失部分的形状。我们使用一种形状的深度学习模型来捕捉前一个方面;对于后者，我们同时将所有区域的能量最小化，并且仅考虑用于数据协议的未被遮挡的像素。包含对象形状先验的现有算法依次考虑每个对象，并且不能区分由于遮挡导致的部分缺失的预期形状的真实偏差。我们表明，我们的方法显着提高了代表性算法的性能，在预处理的自然和合成图像上评估。此外，在合成图像上，我们恢复了精确的地面真实分割。

##### URL
[https://arxiv.org/abs/1606.04590](https://arxiv.org/abs/1606.04590)

##### PDF
[https://arxiv.org/pdf/1606.04590](https://arxiv.org/pdf/1606.04590)

