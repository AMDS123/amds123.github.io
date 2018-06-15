---
layout: post
title: "Identifying Recurring Patterns with Deep Neural Networks for Natural Image Denoising"
date: 2018-06-13 19:11:19
categories: arXiv_CV
tags: arXiv_CV
author: Zhihao Xia, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
While there is a vast diversity in the patterns and textures that occur across different varieties of natural images, the variance of such patterns within a single image is far more limited. A variety of traditional methods have exploited this self-similarity or recurrence with considerable success for image modeling, estimation, and restoration. A key challenge, however, is in accurately identifying recurring patterns within degraded image observations. This work proposes a new method for natural image denoising, that trains a deep neural network to determine whether noisy patches share common underlying patterns. Specifically, given a pair of noisy patches, the network predicts whether different transform sub-band coefficients of the original noise-free patches are the same. The denoising algorithm averages these matched coefficients to obtain an initial estimate of the clean image, with much higher quality than traditional approaches. This estimate is then refined with a second post-processing network, yielding state-of-the-art denoising performance.

##### Abstract (translated by Google)
虽然不同种类的自然图像中出现的图案和纹理存在巨大的差异，但单幅图像内这种图案的变化却受到了更多的限制。各种传统方法已经利用了这种自相似性或者重现性，并且在图像建模，估计和恢复方面取得了相当大的成功。然而，一个关键的挑战是准确地识别退化图像观察中的循环模式。这项工作提出了一种新的自然图像去噪方法，训练一个深度神经网络来确定是否有噪声补丁共享共同的基本模式。具体来说，给定一对噪声片，网络预测原始无噪声片的不同变换子带系数是否相同。去噪算法对这些匹配系数进行平均以获得对干净图像的初始估计，其质量远高于传统方法。然后再用第二个后处理网络对这个估计进行细化，从而得出最先进的去噪表现。

##### URL
[http://arxiv.org/abs/1806.05229](http://arxiv.org/abs/1806.05229)

##### PDF
[http://arxiv.org/pdf/1806.05229](http://arxiv.org/pdf/1806.05229)

