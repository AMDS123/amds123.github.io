---
layout: post
title: "Weaving Multi-scale Context for Single Shot Detector"
date: 2017-12-08 16:16:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yunpeng Chen, Jianshu Li, Bin Zhou, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Aggregating context information from multiple scales has been proved to be effective for improving accuracy of Single Shot Detectors (SSDs) on object detection. However, existing multi-scale context fusion techniques are computationally expensive, which unfavorably diminishes the advantageous speed of SSD. In this work, we propose a novel network topology, called WeaveNet, that can efficiently fuse multi-scale information and boost the detection accuracy with negligible extra cost. The proposed WeaveNet iteratively weaves context information from adjacent scales together to enable more sophisticated context reasoning while maintaining fast speed. Built by stacking light-weight blocks, WeaveNet is easy to train without requiring batch normalization and can be further accelerated by our proposed architecture simplification. Experimental results on PASCAL VOC 2007, PASCAL VOC 2012 benchmarks show signification performance boost brought by WeaveNet. For 320x320 input of batch size = 8, WeaveNet reaches 79.5% mAP on PASCAL VOC 2007 test in 101 fps with only 4 fps extra cost, and further improves to 79.7% mAP with more iterations.

##### Abstract (translated by Google)
已经证明，从多个比例聚合上下文信息对于提高单次探测器（SSD）在物体检测上的准确度是有效的。然而，现有的多尺度上下文融合技术在计算上是昂贵的，这不利地降低了SSD的有利速度。在这项工作中，我们提出了一个新的网络拓扑，称为WeaveNet，可以有效地融合多尺度的信息，提高检测精度，可以忽略额外的成本。所提出的WeaveNet迭代地将来自相邻尺度的上下文信息编织在一起，以在保持较快速度的同时实现更复杂的上下文推理。 WeaveNet通过堆叠轻量级块来构建，不需要批量归一化就可以轻松进行训练，并且可以通过我们提出的架构简化进一步加速。 PASCAL VOC 2007，PASCAL VOC 2012基准的实验结果显示WeaveNet带来了意义上的性能提升。对于批量大小为320x320的输入= 8，WeaveNet在PASCAL VOC 2007测试中以101 fps的速度达到79.5％的mAP，额外成本仅为4 fps，并且随着迭代次数的增加，进一步提高到79.7％。

##### URL
[http://arxiv.org/abs/1712.03149](http://arxiv.org/abs/1712.03149)

##### PDF
[http://arxiv.org/pdf/1712.03149](http://arxiv.org/pdf/1712.03149)

