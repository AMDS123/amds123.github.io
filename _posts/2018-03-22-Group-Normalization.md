---
layout: post
title: "Group Normalization"
date: 2018-03-22 17:57:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Video_Classification Classification Deep_Learning Detection
author: Yuxin Wu, Kaiming He
mathjax: true
---

* content
{:toc}

##### Abstract
Batch Normalization (BN) is a milestone technique in the development of deep learning, enabling various networks to train. However, normalizing along the batch dimension introduces problems --- BN's error increases rapidly when the batch size becomes smaller, caused by inaccurate batch statistics estimation. This limits BN's usage for training larger models and transferring features to computer vision tasks including detection, segmentation, and video, which require small batches constrained by memory consumption. In this paper, we present Group Normalization (GN) as a simple alternative to BN. GN divides the channels into groups and computes within each group the mean and variance for normalization. GN's computation is independent of batch sizes, and its accuracy is stable in a wide range of batch sizes. On ResNet-50 trained in ImageNet, GN has 10.6% lower error than its BN counterpart when using a batch size of 2; when using typical batch sizes, GN is comparably good with BN and outperforms other normalization variants. Moreover, GN can be naturally transferred from pre-training to fine-tuning. GN can outperform or compete with its BN-based counterparts for object detection and segmentation in COCO, and for video classification in Kinetics, showing that GN can effectively replace the powerful BN in a variety of tasks. GN can be easily implemented by a few lines of code in modern libraries.

##### Abstract (translated by Google)
批量标准化（BN）是深度学习发展中的一项里程碑式技术，可让各种网络进行培训。但是，沿着批量维度进行归一化会带来一些问题---批量统计估算不准确导致批量变小时，BN的误差会迅速增加。这限制了BN用于培训更大型号的功能，并将功能转移到计算机视觉任务，包括检测，分割和视频，这些任务都需要受内存消耗限制的小批量处理。在本文中，我们提出组标准化（GN）作为BN的简单替代方案。 GN将通道分成组，并在每组内计算标准化的均值和方差。 GN的计算与批量大小无关，并且其准确度在各种批量大小下都很稳定。在ImageNet上训练的ResNet-50上，GN使用批量大小为2时的错误率比BN对手低10.6％;当使用典型的批量时，GN与BN相当，并且优于其他标准化变量。而且，GN可以自然地从预培训转向微调。 GN可以胜过其竞争对手，或者与其在国阵的对手进行COCO中的目标检测和分割以及Kinetics中的视频分类竞争，表明GN可以在各种任务中有效地取代强大的BN。 GN可以通过现代库中的几行代码轻松实现。

##### URL
[https://arxiv.org/abs/1803.08494](https://arxiv.org/abs/1803.08494)

##### PDF
[https://arxiv.org/pdf/1803.08494](https://arxiv.org/pdf/1803.08494)

