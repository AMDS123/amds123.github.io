---
layout: post
title: "One-Shot Segmentation in Clutter"
date: 2018-03-26 14:07:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Embedding Detection Recognition
author: Claudio Michaelis, Matthias Bethge, Alexander S. Ecker
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of one-shot segmentation: finding and segmenting a previously unseen object in a cluttered scene based on a single instruction example. We propose a baseline architecture combining a Siamese embedding for detection with a U-net for segmentation and evaluate it on a novel dataset, which we call $\textit{cluttered Omniglot}$. Using oracle models with access to various amounts of ground-truth information, we show that in this kind of visual search task, detection and segmentation are two intertwined problems, the solution to each of which helps solving the other. We therefore introduce $\textit{MaskNet}$, an improved model that sequentially attends to different locations, generates segmentation proposals to mask out background clutter and selects among the segmented objects. Our findings suggest that such image recognition models based on an iterative refinement of object detection and foreground segmentation may help improving both detection and segmentation in highly cluttered scenes.

##### Abstract (translated by Google)
我们解决单次分割的问题：根据单个指令示例在混乱的场景中查找和分割以前看不见的对象。我们提出了一个基准体系结构，它将用于检测的连体嵌入与用于分割的U网分开，并在一个新的数据集上进行评估，我们称之为$ \ textit {cluttered Omniglot} $。使用可以访问各种数量的地面真实信息的oracle模型，我们表明在这种视觉搜索任务中，检测和分割是两个交织在一起的问题，每个解决方案都有助于解决另一个问题。因此，我们引入$ \ textit {MaskNet} $，它是一个顺序参与不同位置的改进模型，生成分割建议以掩盖背景混乱并在分割对象中进行选择。我们的研究结果表明，这种基于对象检测和前景分割的迭代改进的图像识别模型可能有助于在高度混乱的场景中改善检测和分割。

##### URL
[https://arxiv.org/abs/1803.09597](https://arxiv.org/abs/1803.09597)

##### PDF
[https://arxiv.org/pdf/1803.09597](https://arxiv.org/pdf/1803.09597)

