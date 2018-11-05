---
layout: post
title: "SDCNet: Video Prediction Using Spatially-Displaced Convolution"
date: 2018-11-02 00:14:05
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Fitsum A. Reda, Guilin Liu, Kevin J. Shih, Robert Kirby, Jon Barker, David Tarjan, Andrew Tao, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for high-resolution video frame prediction by conditioning on both past frames and past optical flows. Previous approaches rely on resampling past frames, guided by a learned future optical flow, or on direct generation of pixels. Resampling based on flow is insufficient because it cannot deal with disocclusions. Generative models currently lead to blurry results. Recent approaches synthesis a pixel by convolving input patches with a predicted kernel. However, their memory requirement increases with kernel size. Here, we spatially-displaced convolution (SDC) module for video frame prediction. We learn a motion vector and a kernel for each pixel and synthesize a pixel by applying the kernel at a displaced location in the source image, defined by the predicted motion vector. Our approach inherits the merits of both vector-based and kernel-based approaches, while ameliorating their respective disadvantages. We train our model on 428K unlabelled 1080p video game frames. Our approach produces state-of-the-art results, achieving an SSIM score of 0.904 on high-definition YouTube-8M videos, 0.918 on Caltech Pedestrian videos. Our model handles large motion effectively and synthesizes crisp frames with consistent motion.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00684](http://arxiv.org/abs/1811.00684)

##### PDF
[http://arxiv.org/pdf/1811.00684](http://arxiv.org/pdf/1811.00684)

