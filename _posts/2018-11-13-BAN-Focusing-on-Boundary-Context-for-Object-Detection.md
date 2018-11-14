---
layout: post
title: "BAN: Focusing on Boundary Context for Object Detection"
date: 2018-11-13 12:10:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yonghyun Kim, Taewook Kim, Bong-Nam Kang, Jieun Kim, Daijin Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Visual context is one of the important clue for object detection and the context information for boundaries of an object is especially valuable. We propose a boundary aware network (BAN) designed to exploit the visual contexts including boundary information and surroundings, named boundary context, and define three types of the boundary contexts: side, vertex and in/out-boundary context. Our BAN consists of 10 sub-networks for the area belonging to the boundary contexts. The detection head of BAN is defined as an ensemble of these sub-networks with different contributions depending on the sub-problem of detection. To verify our method, we visualize the activation of the sub-networks according to the boundary contexts and empirically show that the sub-networks contribute more to the related sub-problem in detection. We evaluate our method on PASCAL VOC detection benchmark and MS COCO dataset. The proposed method achieves the mean Average Precision (mAP) of 83.4% on PASCAL VOC and 36.9% on MS COCO. BAN allows the convolution network to provide an additional source of contexts for detection and selectively focus on the more important contexts, and it can be generally applied to many other detection methods as well to enhance the accuracy in detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05243](http://arxiv.org/abs/1811.05243)

##### PDF
[http://arxiv.org/pdf/1811.05243](http://arxiv.org/pdf/1811.05243)

