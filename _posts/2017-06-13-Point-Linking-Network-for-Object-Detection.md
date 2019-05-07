---
layout: post
title: "Point Linking Network for Object Detection"
date: 2017-06-13 05:04:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xinggang Wang, Kaibing Chen, Zilong Huang, Cong Yao, Wenyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a core problem in computer vision. With the development of deep ConvNets, the performance of object detectors has been dramatically improved. The deep ConvNets based object detectors mainly focus on regressing the coordinates of bounding box, e.g., Faster-R-CNN, YOLO and SSD. Different from these methods that considering bounding box as a whole, we propose a novel object bounding box representation using points and links and implemented using deep ConvNets, termed as Point Linking Network (PLN). Specifically, we regress the corner/center points of bounding-box and their links using a fully convolutional network; then we map the corner points and their links back to multiple bounding boxes; finally an object detection result is obtained by fusing the multiple bounding boxes. PLN is naturally robust to object occlusion and flexible to object scale variation and aspect ratio variation. In the experiments, PLN with the Inception-v2 model achieves state-of-the-art single-model and single-scale results on the PASCAL VOC 2007, the PASCAL VOC 2012 and the COCO detection benchmarks without bells and whistles. The source code will be released.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.03646](https://arxiv.org/abs/1706.03646)

##### PDF
[https://arxiv.org/pdf/1706.03646](https://arxiv.org/pdf/1706.03646)

