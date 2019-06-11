---
layout: post
title: "Deep Robust Single Image Depth Estimation Neural Network Using Scene Understanding"
date: 2019-06-07 18:08:34
categories: arXiv_CV
tags: arXiv_CV Classification
author: Haoyu Ren, Mostafa El-khamy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Single image depth estimation (SIDE) plays a crucial role in 3D computer vision. In this paper, we propose a two-stage robust SIDE framework that can perform blind SIDE for both indoor and outdoor scenes. At the first stage, the scene understanding module will categorize the RGB image into different depth-ranges. We introduce two different scene understanding modules based on scene classification and coarse depth estimation respectively. At the second stage, SIDE networks trained by the images of specific depth-range are applied to obtain an accurate depth map. In order to improve the accuracy, we further design a multi-task encoding-decoding SIDE network DS-SIDENet based on depthwise separable convolutions. DS-SIDENet is optimized to minimize both depth classification and depth regression losses. This improves the accuracy compared to a single-task SIDE network. Experimental results demonstrate that training DS-SIDENet on an individual dataset such as NYU achieves competitive performance to the state-of-art methods with much better efficiency. Ours proposed robust SIDE framework also shows good performance for the ScanNet indoor images and KITTI outdoor images simultaneously. It achieves the top performance compared to the Robust Vision Challenge (ROB) 2018 submissions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03279](http://arxiv.org/abs/1906.03279)

##### PDF
[http://arxiv.org/pdf/1906.03279](http://arxiv.org/pdf/1906.03279)

