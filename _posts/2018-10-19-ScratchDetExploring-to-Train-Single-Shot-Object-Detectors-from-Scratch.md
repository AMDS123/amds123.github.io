---
layout: post
title: "ScratchDet:Exploring to Train Single-Shot Object Detectors from Scratch"
date: 2018-10-19 09:57:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Rui Zhu, Shifeng Zhang, Xiaobo Wang, Longyin Wen, Hailin Shi, Liefeng Bo, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art object objectors are fine-tuned from the off-the-shelf networks pretrained on large-scale classification datasets like ImageNet, which incurs some accessory problems: 1) the domain gap between source and target datasets; 2) the learning objective bias between classification and detection; 3) the architecture limitations of the classification network for detection. In this paper, we design a new single-shot train-from-scratch object detector referring to the architectures of the ResNet and VGGNet based SSD models, called ScratchDet, to alleviate the aforementioned problems. Specifically, we study the impact of BatchNorm on training detectors from scratch, and find that using BatchNorm on the backbone and detection head subnetworks makes the detector converge well from scratch. After that, we explore the network architecture by analyzing the detection performance of ResNet and VGGNet, and introduce a new Root-ResNet backbone network to further improve the accuracy. Extensive experiments on PASCAL VOC 2007, 2012 and MS COCO datasets demonstrate that ScratchDet achieves the state-of-the-art performance among all the train-from-scratch detectors and even outperforms existing one-stage pretrained methods without bells and whistles. Codes will be made publicly available at https://github.com/KimSoybean/ScratchDet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08425](http://arxiv.org/abs/1810.08425)

##### PDF
[http://arxiv.org/pdf/1810.08425](http://arxiv.org/pdf/1810.08425)

