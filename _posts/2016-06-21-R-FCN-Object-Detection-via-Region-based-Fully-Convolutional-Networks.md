---
layout: post
title: "R-FCN: Object Detection via Region-based Fully Convolutional Networks"
date: 2016-06-21 15:28:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection
author: Jifeng Dai, Yi Li, Kaiming He, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We present region-based, fully convolutional networks for accurate and efficient object detection. In contrast to previous region-based detectors such as Fast/Faster R-CNN that apply a costly per-region subnetwork hundreds of times, our region-based detector is fully convolutional with almost all computation shared on the entire image. To achieve this goal, we propose position-sensitive score maps to address a dilemma between translation-invariance in image classification and translation-variance in object detection. Our method can thus naturally adopt fully convolutional image classifier backbones, such as the latest Residual Networks (ResNets), for object detection. We show competitive results on the PASCAL VOC datasets (e.g., 83.6% mAP on the 2007 set) with the 101-layer ResNet. Meanwhile, our result is achieved at a test-time speed of 170ms per image, 2.5-20x faster than the Faster R-CNN counterpart. Code is made publicly available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1605.06409](https://arxiv.org/abs/1605.06409)

##### PDF
[https://arxiv.org/pdf/1605.06409](https://arxiv.org/pdf/1605.06409)

