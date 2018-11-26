---
layout: post
title: "Defect Detection from UAV Images based on Region-Based CNNs"
date: 2018-11-23 13:38:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Meng Lan, Yipeng Zhang, Lefei Zhang, Bo Du
mathjax: true
---

* content
{:toc}

##### Abstract
With the wide applications of Unmanned Aerial Vehicle (UAV) in engineering such as the inspection of the electrical equipment from distance, the demands of efficient object detection algorithms for abundant images acquired by UAV have also been significantly increased in recent years. In this work, we study the performance of the region-based CNN for the electrical equipment defect detection by using the UAV images. In order to train the detection model, we collect a UAV images dataset composes of four classes of electrical equipment defects with thousands of annotated labels. Then, based on the region-based faster R-CNN model, we present a multi-class defects detection model for electrical equipment which is more efficient and accurate than traditional single class detection methods. Technically, we have replaced the RoI pooling layer with a similar operation in Tensorflow and promoted the mini-batch to 128 per image in the training procedure. These improvements have slightly increased the speed of detection without any accuracy loss. Therefore, the modified region-based CNN could simultaneously detect multi-class of defects of the electrical devices in nearly real time. Experimental results on the real word electrical equipment images demonstrate that the proposed method achieves better performance than the traditional object detection algorithms in defect detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09473](http://arxiv.org/abs/1811.09473)

##### PDF
[http://arxiv.org/pdf/1811.09473](http://arxiv.org/pdf/1811.09473)

