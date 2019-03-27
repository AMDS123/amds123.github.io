---
layout: post
title: "DetNAS: Neural Architecture Search on Object Detection"
date: 2019-03-26 16:08:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Yukang Chen, Tong Yang, Xiangyu Zhang, Gaofeng Meng, Chunhong Pan, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors are usually equipped with networks designed for image classification as backbones, e.g., ResNet. Although it is publicly known that there is a gap between the task of image classification and object detection, designing a suitable detector backbone is still manually exhaustive. In this paper, we propose DetNAS to automatically search neural architectures for the backbones of object detectors. In DetNAS, the search space is formulated into a supernet and the search method relies on evolution algorithm (EA). In experiments, we show the effectiveness of DetNAS on various detectors, the one-stage detector, RetinaNet, and the two-stage detector, FPN. For each case, we search in both training from scratch scheme and ImageNet pre-training scheme. There is a consistent superiority compared to the architectures searched on ImageNet classification. Our main result architecture achieves better performance than ResNet-101 on COCO with the FPN detector. In addition, we illustrate the architectures searched by DetNAS and find some meaningful patterns.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10979](http://arxiv.org/abs/1903.10979)

##### PDF
[http://arxiv.org/pdf/1903.10979](http://arxiv.org/pdf/1903.10979)

