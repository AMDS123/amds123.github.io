---
layout: post
title: "Learning to Segment Instances in Videos with Spatial Propagation Network"
date: 2017-09-14 04:15:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Jingchun Cheng, Sifei Liu, Yi-Hsuan Tsai, Wei-Chih Hung, Shalini De Mello, Jinwei Gu, Jan Kautz, Shengjin Wang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep learning-based framework for instance-level object segmentation. Our method mainly consists of three steps. First, We train a generic model based on ResNet-101 for foreground/background segmentations. Second, based on this generic model, we fine-tune it to learn instance-level models and segment individual objects by using augmented object annotations in first frames of test videos. To distinguish different instances in the same video, we compute a pixel-level score map for each object from these instance-level models. Each score map indicates the objectness likelihood and is only computed within the foreground mask obtained in the first step. To further refine this per frame score map, we learn a spatial propagation network. This network aims to learn how to propagate a coarse segmentation mask spatially based on the pairwise similarities in each frame. In addition, we apply a filter on the refined score map that aims to recognize the best connected region using spatial and temporal consistencies in the video. Finally, we decide the instance-level object segmentation in each video by comparing score maps of different instances.

##### Abstract (translated by Google)
我们提出了一个深入的基于学习的框架实例级对象分割。我们的方法主要由三个步骤组成。首先，我们训练一个基于ResNet-101的通用模型，用于前景/背景分割。其次，基于这个通用模型，我们对它进行微调以学习实例级模型，并通过在测试视频的第一帧中使用增强对象注释来分割单个对象。为了区分同一视频中的不同实例，我们从这些实例级模型中为每个对象计算像素级评分图。每个得分图指示对象可能性，并且仅在第一步中获得的前景掩模内计算。为了进一步细化这个每帧评分图，我们学习了一个空间传播网络。该网络旨在学习如何基于每帧中的成对相似性在空间上传播粗分割掩模。另外，我们在精化分数图上应用一个滤波器，旨在利用视频中的空间和时间一致性来识别最佳连通区域。最后，我们通过比较不同实例的分数图来确定每个视频中的实例级对象分割。

##### URL
[https://arxiv.org/abs/1709.04609](https://arxiv.org/abs/1709.04609)

##### PDF
[https://arxiv.org/pdf/1709.04609](https://arxiv.org/pdf/1709.04609)

