---
layout: post
title: "Adaptive Temporal Encoding Network for Video Instance-level Human Parsing"
date: 2018-08-02 04:24:36
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Qixian Zhou, Xiaodan Liang, Ke Gong, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Beyond the existing single-person and multiple-person human parsing tasks in static images, this paper makes the first attempt to investigate a more realistic video instance-level human parsing that simultaneously segments out each person instance and parses each instance into more fine-grained parts (e.g., head, leg, dress). We introduce a novel Adaptive Temporal Encoding Network (ATEN) that alternatively performs temporal encoding among key frames and flow-guided feature propagation from other consecutive frames between two key frames. Specifically, ATEN first incorporates a Parsing-RCNN to produce the instance-level parsing result for each key frame, which integrates both the global human parsing and instance-level human segmentation into a unified model. To balance between accuracy and efficiency, the flow-guided feature propagation is used to directly parse consecutive frames according to their identified temporal consistency with key frames. On the other hand, ATEN leverages the convolution gated recurrent units (convGRU) to exploit temporal changes over a series of key frames, which are further used to facilitate the frame-level instance-level parsing. By alternatively performing direct feature propagation between consistent frames and temporal encoding network among key frames, our ATEN achieves a good balance between frame-level accuracy and time efficiency, which is a common crucial problem in video object segmentation research. To demonstrate the superiority of our ATEN, extensive experiments are conducted on the most popular video segmentation benchmark (DAVIS) and a newly collected Video Instance-level Parsing (VIP) dataset, which is the first video instance-level human parsing dataset comprised of 404 sequences and over 20k frames with instance-level and pixel-wise annotations.

##### Abstract (translated by Google)
除了静态图像中现有的单人和多人解析任务之外，本文首次尝试研究更逼真的视频实例级人工解析，同时将每个人实例分段并将每个实例解析为更细粒度的零件（例如头部，腿部，连衣裙）。我们介绍了一种新颖的自适应时间编码网络（ATEN），它可以在关键帧之间交替执行时间编码，并从两个关键帧之间的其他连续帧中进行流导引特征传播。具体来说，ATEN首先结合Parsing-RCNN来为每个关键帧生成实例级解析结果，它将全局人工解析和实例级人工划分集成到统一模型中。为了在准确性和效率之间进行平衡，流导向特征传播用于根据与关键帧识别的时间一致性直接解析连续帧。另一方面，ATEN利用卷积门控循环单元（convGRU）来利用一系列关键帧的时间变化，这些关键帧进一步用于促进帧级实例级解析。通过在关键帧之间交替执行一致帧和时间编码网络之间的直接特征传播，我们的ATEN在帧级精度和时间效率之间实现了良好的平衡，这是视频对象分割研究中的常见关键问题。为了证明我们的ATEN的优越性，在最流行的视频分割基准（DAVIS）和新收集的视频实例级解析（VIP）数据集上进行了大量实验，这是第一个由404组成的视频实例级人类解析数据集。具有实例级和逐像素注释的序列和超过20k帧。

##### URL
[http://arxiv.org/abs/1808.00661](http://arxiv.org/abs/1808.00661)

##### PDF
[http://arxiv.org/pdf/1808.00661](http://arxiv.org/pdf/1808.00661)

