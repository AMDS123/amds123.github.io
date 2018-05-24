---
layout: post
title: "RGB-T Object Tracking:Benchmark and Baseline"
date: 2018-05-23 07:13:39
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Object_Tracking Optimization
author: Chenglong Li, Xinyan Liang, Yijuan Lu, Nan Zhao, Jin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
RGB-Thermal (RGB-T) object tracking receives more and more attention due to the strongly complementary benefits of thermal information to visible data. However, RGB-T research is limited by lacking a comprehensive evaluation platform. In this paper, we propose a large-scale video benchmark dataset for RGB-T tracking.It has three major advantages over existing ones: 1) Its size is sufficiently large for large-scale performance evaluation (total frame number: 234K, maximum frame per sequence: 8K). 2) The alignment between RGB-T sequence pairs is highly accurate, which does not need pre- or post-processing. 3) The occlusion levels are annotated for occlusion-sensitive performance analysis of different tracking algorithms.Moreover, we propose a novel graph-based approach to learn a robust object representation for RGB-T tracking. In particular, the tracked object is represented with a graph with image patches as nodes. This graph including graph structure, node weights and edge weights is dynamically learned in a unified ADMM (alternating direction method of multipliers)-based optimization framework, in which the modality weights are also incorporated for adaptive fusion of multiple source data.Extensive experiments on the large-scale dataset are executed to demonstrate the effectiveness of the proposed tracker against other state-of-the-art tracking methods. We also provide new insights and potential research directions to the field of RGB-T object tracking.

##### Abstract (translated by Google)
由于热信息对可视数据的强大互补优势，RGB-Thermal（RGB-T）对象跟踪受到越来越多的关注。但是，由于缺乏全面的评估平​​台，RGB-T研究受到限制。在本文中，我们提出了一个用于RGB-T跟踪的大规模视频基准数据集，它具有三个主要优势：1）其大小足够大，用于大规模性能评估（总帧数：234K，最大帧数每个序列：8K）。 2）RGB-T序列对之间的对齐非常准确，不需要预处理或后处理。 3）针对不同跟踪算法的遮挡敏感性能分析，对遮挡水平进行了标注。另外，我们提出了一种基于图的新方法来学习RGB-T跟踪的鲁棒对象表示。具体而言，被跟踪的对象用具有图像块作为节点的图形表示。该图包括图结构，节点权重和边权重在动态学习的统一ADMM（交替方向乘法器）为基础的优化框架，其中模态权重也纳入多源数据的自适应融合。大量的实验大规模数据集被执行以证明所提议的跟踪器对付其他最先进的跟踪方法的有效性。我们还为RGB-T目标跟踪领域提供新的见解和潜在的研究方向。

##### URL
[http://arxiv.org/abs/1805.08982](http://arxiv.org/abs/1805.08982)

##### PDF
[http://arxiv.org/pdf/1805.08982](http://arxiv.org/pdf/1805.08982)

