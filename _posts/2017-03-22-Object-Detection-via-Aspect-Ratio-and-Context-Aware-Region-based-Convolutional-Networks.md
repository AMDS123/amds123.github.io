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
联合整合纵横比和上下文已经被广泛地研究，并且在诸如DPM的传统物体检测系统中显示了性能改进。然而，它在基于深度神经网络的检测系统中基本上被忽略了。本文提出了一种融合对象模型和区域卷积网络的混合方法，以实现精确的对象检测。每个混合组件都明确地考虑了对象的纵横比和多尺度的上下文信息：（1）它利用了RoI池中拼贴配置的混合来弥补单一类型RoI池引起的翘曲伪像（例如， 7×7个单元格），并更多地尊重潜在的对象形状; （二）“从外部和内部看待投资回报”，将情景信息纳入两个层面：从整个形象汇集而来的全球背景和从投资回收周围汇集的当地情况。为了便于准确检测，本文提出了一种多级检测方案，用于对目标模型进行融合，利用前一阶段模型的检测结果作为目前训练和检测的建议。该方法被称为长宽比和上下文感知基于区域的卷积网络（ARC-R-CNN）。在实验中，ARC-R-CNN在两个数据集（PASCAL VOC和Microsoft COCO）上用更快的R-CNN [41]和R-FCN [10]显示出非常有竞争力的结果。它在两个数据集上使用高IoU阈值获得显着更好的MAP性能。

##### URL
[https://arxiv.org/abs/1612.00534](https://arxiv.org/abs/1612.00534)

##### PDF
[https://arxiv.org/pdf/1612.00534](https://arxiv.org/pdf/1612.00534)

