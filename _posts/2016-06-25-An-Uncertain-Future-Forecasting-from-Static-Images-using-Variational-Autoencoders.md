---
layout: post
title: "An Uncertain Future: Forecasting from Static Images using Variational Autoencoders"
date: 2016-06-25 05:56:46
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Jacob Walker, Carl Doersch, Abhinav Gupta, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
In a given scene, humans can often easily predict a set of immediate future events that might happen. However, generalized pixel-level anticipation in computer vision systems is difficult because machine learning struggles with the ambiguity inherent in predicting the future. In this paper, we focus on predicting the dense trajectory of pixels in a scene, specifically what will move in the scene, where it will travel, and how it will deform over the course of one second. We propose a conditional variational autoencoder as a solution to this problem. In this framework, direct inference from the image shapes the distribution of possible trajectories, while latent variables encode any necessary information that is not available in the image. We show that our method is able to successfully predict events in a wide variety of scenes and can produce multiple different predictions when the future is ambiguous. Our algorithm is trained on thousands of diverse, realistic videos and requires absolutely no human labeling. In addition to non-semantic action prediction, we find that our method learns a representation that is applicable to semantic vision tasks.

##### Abstract (translated by Google)
在一个特定的场景中，人类通常可以很容易地预测可能发生的一系列即将来临的事件。然而，计算机视觉系统中广义的像素级预测是困难的，因为机器学习与预测未来固有的模糊性是矛盾的。在本文中，我们着重于预测场景中像素的密集轨迹，特别是将在场景中移动的位置，移动的位置以及如何在一秒内变形。我们提出了一个条件变分自动编码器作为解决这个问题的方法。在这个框架中，从图像直接推理形成可能轨迹的分布，而潜在变量编码图像中不可用的任何必要信息。我们表明，我们的方法能够成功地预测各种场景中的事件，并且当将来模糊时可以产生多种不同的预测。我们的算法经过数千种不同的逼真视频的训练，绝对不需要人工标记。除了非语义行为预测之外，我们发现我们的方法学习了适用于语义视觉任务的表示。

##### URL
[https://arxiv.org/abs/1606.07873](https://arxiv.org/abs/1606.07873)

##### PDF
[https://arxiv.org/pdf/1606.07873](https://arxiv.org/pdf/1606.07873)

