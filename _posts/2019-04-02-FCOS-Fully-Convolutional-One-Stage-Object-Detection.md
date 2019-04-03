---
layout: post
title: "FCOS: Fully Convolutional One-Stage Object Detection"
date: 2019-04-02 11:56:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Prediction Detection
author: Zhi Tian, Chunhua Shen, Hao Chen, Tong He
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fully convolutional one-stage object detector (FCOS) to solve object detection in a per-pixel prediction fashion, analogue to semantic segmentation. Almost all state-of-the-art object detectors such as RetinaNet, SSD, YOLOv3, and Faster R-CNN rely on pre-defined anchor boxes. In contrast, our proposed detector FCOS is anchor-box free, as well as proposal free. By eliminating the pre-defined set of anchor boxes, FCOS completely avoids the complicated computation related to anchor boxes such as calculating overlapping during training and significantly reduces the training memory footprint. More importantly, we also avoid all hyper-parameters related to anchor boxes, which are often very sensitive to the final detection performance. With the only post-processing non-maximum suppression (NMS), our detector FCOS outperforms previous anchor-based one-stage detectors with the advantage of being much simpler. For the first time, we demonstrate a much simpler and flexible detection framework achieving improved detection accuracy. We hope that the proposed FCOS framework can serve as a simple and strong alternative for many other instance-level tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01355](http://arxiv.org/abs/1904.01355)

##### PDF
[http://arxiv.org/pdf/1904.01355](http://arxiv.org/pdf/1904.01355)

