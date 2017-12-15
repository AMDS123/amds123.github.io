---
layout: post
title: "Behavior Discovery and Alignment of Articulated Object Classes from Unstructured Video"
date: 2016-08-11 01:29:20
categories: arXiv_CV
tags: arXiv_CV GAN
author: Luca Del Pero, Susanna Ricco, Rahul Sukthankar, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an automatic system for organizing the content of a collection of unstructured videos of an articulated object class (e.g. tiger, horse). By exploiting the recurring motion patterns of the class across videos, our system: 1) identifies its characteristic behaviors; and 2) recovers pixel-to-pixel alignments across different instances. Our system can be useful for organizing video collections for indexing and retrieval. Moreover, it can be a platform for learning the appearance or behaviors of object classes from Internet video. Traditional supervised techniques cannot exploit this wealth of data directly, as they require a large amount of time-consuming manual annotations. The behavior discovery stage generates temporal video intervals, each automatically trimmed to one instance of the discovered behavior, clustered by type. It relies on our novel motion representation for articulated motion based on the displacement of ordered pairs of trajectories (PoTs). The alignment stage aligns hundreds of instances of the class to a great accuracy despite considerable appearance variations (e.g. an adult tiger and a cub). It uses a flexible Thin Plate Spline deformation model that can vary through time. We carefully evaluate each step of our system on a new, fully annotated dataset. On behavior discovery, we outperform the state-of-the-art Improved DTF descriptor. On spatial alignment, we outperform the popular SIFT Flow algorithm.

##### Abstract (translated by Google)
我们提出了一个自动系统，用于组织关节目标类别（如虎，马）的非结构化视频集合的内容。我们的系统通过利用视频中类别的反复运动模式：1）识别其特征行为;和2）恢复不同实例间的像素对像素对齐。我们的系统可以用于组织视频收藏索引和检索。而且，它可以作为从Internet视频中学习对象类的外观或行为的平台。传统的监督技术不能直接利用这些丰富的数据，因为它们需要大量耗时的手动注释。行为发现阶段产生时间视频时间间隔，每个时间间隔自动修剪为发现的行为的一个实例，按照类型聚类。它依赖于我们基于有序轨道对（PoT）的位移的新颖的运动表示来进行关节运动。尽管有相当多的外观变化（例如，成年的老虎和幼仔），对齐阶段仍然以很高的准确性对齐数百个课程实例。它使用灵活的薄板样条变形模型，可以随时间变化。我们仔细评估我们的系统的每一步在一个新的，充分注释的数据集。在行为发现上，我们超越了最先进的改进的DTF描述符。在空间对齐方面，我们胜过了流行的SIFT流算法。

##### URL
[https://arxiv.org/abs/1511.09319](https://arxiv.org/abs/1511.09319)

##### PDF
[https://arxiv.org/pdf/1511.09319](https://arxiv.org/pdf/1511.09319)

