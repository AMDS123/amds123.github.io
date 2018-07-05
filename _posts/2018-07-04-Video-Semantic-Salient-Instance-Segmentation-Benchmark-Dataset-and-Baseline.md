---
layout: post
title: "Video Semantic Salient Instance Segmentation: Benchmark Dataset and Baseline"
date: 2018-07-04 05:30:52
categories: arXiv_CV
tags: arXiv_CV Salient Semantic_Instance_Segmentation Segmentation Tracking
author: Trung-Nghia Le, Akihiro Sugimoto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper pushes the envelope on salient regions in a video to decompose them into semantically meaningful components, semantic salient instances. To address this video semantic salient instance segmentation, we construct a new dataset, Semantic Salient Instance Video (SESIV) dataset. Our SESIV dataset consists of 84 high-quality video sequences with pixel-wisely per-frame ground-truth labels annotated for different segmentation tasks. We also provide a baseline for this problem, called Fork-Join Strategy (FJS). FJS is a two-stream network leveraging advantages of two different segmentation tasks, i.e., semantic instance segmentation and salient object segmentation. In FJS, we introduce a sequential fusion that combines the outputs of the two streams to have non-overlapping instances one by one. We also introduce a recurrent instance propagation to refine the shapes and semantic meanings of instances, and an identity tracking to maintain both the identity and the semantic meaning of an instance over the entire video. Experimental results demonstrated the effectiveness of our proposed FJS.

##### Abstract (translated by Google)
本文将信封推到视频中的显着区域，将它们分解为语义上有意义的组件，即语义显着实例。为了解决这个视频语义显着实例分割，我们构建了一个新的数据集，即语义显着实例视频（SESIV）数据集。我们的SESIV数据集由84个高质量的视频序列组成，每个帧的地面实况标签按照不同的分段任务进行注释。我们还为此问题提供了一个基线，称为Fork-Join Strategy（FJS）。 FJS是利用两个不同分段任务的优点的双流网络，即语义实例分割和显着对象分割。在FJS中，我们引入了一种顺序融合，它将两个流的输出结合起来，逐个具有非重叠的实例。我们还引入了一个循环实例传播来优化实例的形状和语义含义，并引入一个身份跟踪来维护整个视频中实例的身份和语义。实验结果证明了我们提出的FJS的有效性。

##### URL
[http://arxiv.org/abs/1807.01452](http://arxiv.org/abs/1807.01452)

##### PDF
[http://arxiv.org/pdf/1807.01452](http://arxiv.org/pdf/1807.01452)

