---
layout: post
title: "Object Detection via Aspect Ratio and Context Aware Region-based Convolutional Networks"
date: 2017-03-22 16:28:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Bo Li, Tianfu Wu, Shuai Shao, Lun Zhang, Rufeng Chu
mathjax: true
---

* content
{:toc}

##### Abstract
Jointly integrating aspect ratio and context has been extensively studied and shown performance improvement in traditional object detection systems such as the DPMs. It, however, has been largely ignored in deep neural network based detection systems. This paper presents a method of integrating a mixture of object models and region-based convolutional networks for accurate object detection. Each mixture component accounts for both object aspect ratio and multi-scale contextual information explicitly: (i) it exploits a mixture of tiling configurations in the RoI pooling to remedy the warping artifacts caused by a single type RoI pooling (e.g., with equally-sized 7 x 7 cells), and to respect the underlying object shapes more; (ii) it "looks from both the inside and the outside of a RoI" by incorporating contextual information at two scales: global context pooled from the whole image and local context pooled from the surrounding of a RoI. To facilitate accurate detection, this paper proposes a multi-stage detection scheme for integrating the mixture of object models, which utilizes the detection results of the model at the previous stage as the proposals for the current in both training and testing. The proposed method is called the aspect ratio and context aware region-based convolutional network (ARC-R-CNN). In experiments, ARC-R-CNN shows very competitive results with Faster R-CNN [41] and R-FCN [10] on two datasets: the PASCAL VOC and the Microsoft COCO. It obtains significantly better mAP performance using high IoU thresholds on both datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.00534](https://arxiv.org/abs/1612.00534)

##### PDF
[https://arxiv.org/pdf/1612.00534](https://arxiv.org/pdf/1612.00534)

