---
layout: post
title: "Creating Lightweight Object Detectors with Model Compression for Deployment on Edge Devices"
date: 2019-05-06 01:52:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Yiwu Yao, Weiqiang Yang, Haoqi Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
To achieve lightweight object detectors for deployment on the edge devices, an effective model compression pipeline is proposed in this paper. The compression pipeline consists of automatic channel pruning for the backbone, fixed channel deletion for the branch layers and knowledge distillation for the guidance learning. As results, the Resnet50-v1d is auto-pruned and fine-tuned on ImageNet to attain a compact base model as the backbone of object detector. Then, lightweight object detectors are implemented with proposed compression pipeline. For instance, the SSD-300 with model size=16.3MB, FLOPS=2.31G, and mAP=71.2 is created, revealing a better result than SSD-300-MobileNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01787](http://arxiv.org/abs/1905.01787)

##### PDF
[http://arxiv.org/pdf/1905.01787](http://arxiv.org/pdf/1905.01787)

