---
layout: post
title: "A Lightweight Optical Flow CNN -- Revisiting Data Fidelity and Regularization"
date: 2019-03-15 04:20:58
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference
author: Tak-Wai Hui, Xiaoou Tang, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Over four decades, the majority addresses the problem of optical flow estimation using variational methods. With the advance of machine learning, some recent works have attempted to address the problem using convolutional neural network (CNN) and have showed promising results. FlowNet2, the state-of-the-art CNN, requires over 160M parameters to achieve accurate flow estimation. Our LiteFlowNet2 outperforms FlowNet2 on Sintel and KITTI benchmarks, while being 25.3 times smaller in the footprint and 3.1 times faster in the running speed. LiteFlowNet2 which is built on the foundation laid by conventional methods has marked a milestone to achieve the corresponding roles as data fidelity and regularization in variational methods. We present an effective flow inference approach at each pyramid level through a novel lightweight cascaded network. It provides high flow estimation accuracy through early correction with seamless incorporation of descriptor matching. A novel flow regularization layer is used to ameliorate the issue of outliers and vague flow boundaries through a novel feature-driven local convolution. Our network also owns an effective structure for pyramidal feature extraction and embraces feature warping rather than image warping as practiced in FlowNet2. Comparing to our earlier work, LiteFlowNet2 improves the optical flow accuracy on Sintel clean pass by 24%, Sintel final pass by 8.9%, KITTI 2012 by 16.8%, and KITTI 2015 by 17.5%. Our network protocol and trained models will be made publicly available on https://github.com/twhui/LiteFlowNet2 .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07414](http://arxiv.org/abs/1903.07414)

##### PDF
[http://arxiv.org/pdf/1903.07414](http://arxiv.org/pdf/1903.07414)

