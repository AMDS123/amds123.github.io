---
layout: post
title: "Deep Perceptual Compression"
date: 2019-07-18 22:17:52
categories: arXiv_CV
tags: arXiv_CV Detection
author: Yash Patel, Srikar Appalaraju, R. Manmatha
mathjax: true
---

* content
{:toc}

##### Abstract
Several deep learned lossy compression techniques have been proposed in the recent literature. Most of these are optimized by using either MS-SSIM (multi-scale structural similarity) or MSE (mean squared error) as a loss function. Unfortunately, neither of these correlate well with human perception and this is clearly visible from the resulting compressed images. In several cases, the MS-SSIM for deep learned techniques is higher than say a conventional, non-deep learned codec such as JPEG-2000 or BPG. However, the images produced by these deep learned techniques are in many cases clearly worse to human eyes than those produced by JPEG-2000 or BPG. 
 We propose the use of an alternative, deep perceptual metric, which has been shown to align better with human perceptual similarity. We then propose Deep Perceptual Compression (DPC) which makes use of an encoder-decoder based image compression model to jointly optimize on the deep perceptual metric and MS-SSIM. Via extensive human evaluations, we show that the proposed method generates visually better results than previous learning based compression methods and JPEG-2000, and is comparable to BPG. Furthermore, we demonstrate that for tasks like object-detection, images compressed with DPC give better accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08310](http://arxiv.org/abs/1907.08310)

##### PDF
[http://arxiv.org/pdf/1907.08310](http://arxiv.org/pdf/1907.08310)

