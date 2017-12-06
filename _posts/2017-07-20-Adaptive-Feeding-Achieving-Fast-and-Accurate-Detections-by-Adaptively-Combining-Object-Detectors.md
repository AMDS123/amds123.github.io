---
layout: post
title: "Adaptive Feeding: Achieving Fast and Accurate Detections by Adaptively Combining Object Detectors"
date: 2017-07-20 07:22:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hong-Yu Zhou, Bin-Bin Gao, Jianxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection aims at high speed and accuracy simultaneously. However, fast models are usually less accurate, while accurate models cannot satisfy our need for speed. A fast model can be 10 times faster but 50\% less accurate than an accurate model. In this paper, we propose Adaptive Feeding (AF) to combine a fast (but less accurate) detector and an accurate (but slow) detector, by adaptively determining whether an image is easy or hard and choosing an appropriate detector for it. In practice, we build a cascade of detectors, including the AF classifier which make the easy vs. hard decision and the two detectors. The AF classifier can be tuned to obtain different tradeoff between speed and accuracy, which has negligible training time and requires no additional training data. Experimental results on the PASCAL VOC, MS COCO and Caltech Pedestrian datasets confirm that AF has the ability to achieve comparable speed as the fast detector and comparable accuracy as the accurate one at the same time. As an example, by combining the fast SSD300 with the accurate SSD500 detector, AF leads to 50\% speedup over SSD500 with the same precision on the VOC2007 test set.

##### Abstract (translated by Google)
目标检测同时以高速度和高精度为目标。然而，快速模型通常不太准确，而准确的模型不能满足我们对速度的需求。快速模型比精确模型快10倍，但精确度低50％。在本文中，我们通过自适应地确定图像是否容易或难以选择合适的检测器来提出自适应进料（AF）来组合快速（但不太精确）的检测器和准确（但是慢）的检测器。在实践中，我们建立了一个级联的检测器，包括使得易于硬判决的AF分类器和两个检测器。可以对AF分类器进行调整，以获得速度和准确度之间的不同折衷，这可以忽略不计的训练时间，并且不需要额外的训练数据。 PASCAL VOC，MS COCO和Caltech行人数据集上的实验结果证实，AF具有与快速检测器相当的速度，与同时精确的速度相当。例如，通过将快速SSD300与准确的SSD500检测器相结合，AF在VOC5007测试装置上的精度相当于SSD500的50％以上。

##### URL
[https://arxiv.org/abs/1707.06399](https://arxiv.org/abs/1707.06399)

