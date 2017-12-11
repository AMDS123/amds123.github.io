---
layout: post
title: "Multi-Scale Video Frame-Synthesis Network with Transitive Consistency Loss"
date: 2017-12-07 22:01:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization
author: Zhe Hu, Yinglan Ma, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional approaches to interpolating/extrapolating frames in a video sequence require accurate pixel correspondences between images, e.g., using optical flow. Their results stem on the accuracy of optical flow estimation, and would generate heavy artifacts when flow estimation failed. Recent methods using auto-encoder have shown impressive progress, however they are usually trained for specific interpolation/extrapolation settings and lack of flexibility and generality for more applications. Moreover, these models are usually heavy in terms of model size which constrains applications on mobile devices. In order to reduce these limitations, we propose a unified network to parameterize the interest frame position and therefore infer interpolated/extrapolated frames within the same framework. To better regularize the network, we introduce a transitive consistency loss and train the network with adversarial training. We adopt a multi-scale structure for the network so that the parameters can be shared across multi-layers. Our approach avoids expensive global optimization of optical flow methods, and is efficient and flexible for video interpolation/extrapolation applications. Experimental results have shown that our method performs favorably against state-of-the-art methods.

##### Abstract (translated by Google)
在视频序列中插入/外插帧的传统方法需要图像之间的准确像素对应，例如使用光流。他们的结果取决于光流估计的准确性，并且在流量估计失败时会产生大量的伪像。最近使用自动编码器的方法已经显示出了令人瞩目的进步，但是它们通常被训练用于特定的内插/外插设置，并且缺乏用于更多应用的灵活性和一般性。而且，这些模型在模型尺寸方面通常很重，这限制了移动设备上的应用。为了减少这些限制，我们提出了一个统一的网络来参数化兴趣帧的位置，从而推断相同框架内的内插/外插帧。为了更好地规范网络，我们引入传递一致性损失，并训练网络进行对抗训练。我们采用多尺度结构的网络，使参数可以跨多层共享。我们的方法避免了昂贵的光流方法的全局优化，并且对于视频插值/外插应用是高效和灵活的。实验结果表明，我们的方法有利于最先进的方法。

##### URL
[http://arxiv.org/abs/1712.02874](http://arxiv.org/abs/1712.02874)

##### PDF
[http://arxiv.org/pdf/1712.02874](http://arxiv.org/pdf/1712.02874)

