---
layout: post
title: "ScratchDet: Training Single-Shot Object Detectors from Scratch"
date: 2019-05-06 03:33:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Classification Detection
author: Rui Zhu, Shifeng Zhang, Xiaobo Wang, Longyin Wen, Hailin Shi, Liefeng Bo, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art object objectors are fine-tuned from the off-the-shelf networks pretrained on large-scale classification dataset ImageNet, which incurs some additional problems: 1) The classification and detection have different degrees of sensitivity to translation, resulting in the learning objective bias; 2) The architecture is limited by the classification network, leading to the inconvenience of modification. To cope with these problems, training detectors from scratch is a feasible solution. However, the detectors trained from scratch generally perform worse than the pretrained ones, even suffer from the convergence issue in training. In this paper, we explore to train object detectors from scratch robustly. By analysing the previous work on optimization landscape, we find that one of the overlooked points in current trained-from-scratch detector is the BatchNorm. Resorting to the stable and predictable gradient brought by BatchNorm, detectors can be trained from scratch stably while keeping the favourable performance independent to the network architecture. Taking this advantage, we are able to explore various types of networks for object detection, without suffering from the poor convergence. By extensive experiments and analyses on downsampling factor, we propose the Root-ResNet backbone network, which makes full use of the information from original images. Our ScratchDet achieves the state-of-the-art accuracy on PASCAL VOC 2007, 2012 and MS COCO among all the train-from-scratch detectors and even performs better than several one-stage pretrained methods. Codes will be made publicly available at https://github.com/KimSoybean/ScratchDet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08425](http://arxiv.org/abs/1810.08425)

##### PDF
[http://arxiv.org/pdf/1810.08425](http://arxiv.org/pdf/1810.08425)

