---
layout: post
title: "Learning Instance-Aware Object Detection Using Determinantal Point Processes"
date: 2018-05-28 04:25:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Nuri Kim, Donghoon Lee, Songhwai Oh
mathjax: true
---

* content
{:toc}

##### Abstract
Recent object detectors find instances while categorizing candidate regions in an input image. As each region is evaluated independently, the number of candidate regions from a detector is usually larger than the number of objects. Since the final goal of detection is to assign a single detection to each object, an additional algorithm, such as non-maximum suppression (NMS), is used to select a single bounding box for an object. While simple heuristic algorithms, such as NMS, are effective for stand-alone objects, they can fail to detect overlapped objects. In this paper, we address this issue by training a network to distinguish different objects while localizing and categorizing them. We propose an instance-aware detection network (IDNet), which can learn to extract features from candidate regions and measures their similarities. Based on pairwise similarities and detection qualities, the IDNet selects an optimal subset of candidate bounding boxes using determinantal point processes (DPPs). Extensive experiments demonstrate that the proposed algorithm performs favorably compared to existing state-of-the-art detection methods particularly for overlapped objects on the PASCAL VOC and MS COCO datasets.

##### Abstract (translated by Google)
最近的对象检测器在对输入图像中的候选区域进行分类时找到实例。由于每个区域都是独立评估的，所以来自探测器的候选区域的数量通常大于对象的数量。由于检测的最​​终目标是为每个对象分配单个检测，因此使用附加算法（如非最大抑制（NMS））为对象选择单个边界框。虽然简单的启发式算法（如NMS）对独立对象有效，但它们可能无法检测到重叠对象。在本文中，我们通过训练网络来解决这个问题，以区分不同的对象，同时对它们进行本地化和分类。我们提出了一个实例感知检测网络（IDNet），它可以学习从候选区域提取特征并测量它们的相似性。基于配对相似性和检测质量，IDNet使用行列式点过程（DPP）选择候选边界框的最佳子集。大量的实验证明，与现有的最先进的检测方法相比，所提出的算法性能更好，特别是对于PASCAL VOC和MS COCO数据集上的重叠对象。

##### URL
[http://arxiv.org/abs/1805.10765](http://arxiv.org/abs/1805.10765)

##### PDF
[http://arxiv.org/pdf/1805.10765](http://arxiv.org/pdf/1805.10765)

