---
layout: post
title: "Pseudo Mask Augmented Object Detection"
date: 2018-03-15 16:51:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Inference Detection
author: Xiangyun Zhao, Shuang Liang, Yichen Wei
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a novel and effective framework to facilitate object detection with the instance-level segmentation information that is only supervised by bounding box annotation. Starting from the joint object detection and instance segmentation network, we propose to recursively estimate the pseudo ground-truth object masks from the instance-level object segmentation network training, and then enhance the detection network with top-down segmentation feedbacks. The pseudo ground truth mask and network parameters are optimized alternatively to mutually benefit for each other. To obtain the promising pseudo masks in each iteration, we embed a graphical inference that incorporates the low-level image appearance consistency and the bounding box annotations to refine the segmentation masks predicted by the segmentation network. Our approach progressively improves the object detection performance by incorporating the detailed pixel-wise information learned from the weakly-supervised segmentation network. Extensive evaluation on the detection task in PASCAL VOC 2007 and 2012 [12] verifies that the proposed approach is effective.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个新颖而有效的框架，以利用仅由边框注解监督的实例级分割信息来促进对象检测。从联合对象检测和实例分割网络开始，我们提出从实例级对象分割网络训练中递归地估计伪地面真实对象掩码，然后利用自顶向下分割反馈增强检测网络。伪地面真实掩模和网络参数被优化以替代彼此互惠。为了在每次迭代中获得有前途的伪掩码，我们嵌入了包含低级图像外观一致性和边界框注释的图形推断，以细化由分割网络预测的分割掩模。我们的方法通过结合从弱监督分割网络学习的详细的逐像素信息来逐步提高对象检测性能。对PASCAL VOC 2007和2012 [12]中的检测任务的广泛评估证实了所提出的方法是有效的。

##### URL
[https://arxiv.org/abs/1803.05858](https://arxiv.org/abs/1803.05858)

##### PDF
[https://arxiv.org/pdf/1803.05858](https://arxiv.org/pdf/1803.05858)

