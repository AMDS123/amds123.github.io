---
layout: post
title: "Clockwork Convnets for Video Semantic Segmentation"
date: 2016-08-11 20:32:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Recognition
author: Evan Shelhamer, Kate Rakelly, Judy Hoffman, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen tremendous progress in still-image segmentation; however the na\"ive application of these state-of-the-art algorithms to every video frame requires considerable computation and ignores the temporal continuity inherent in video. We propose a video recognition framework that relies on two key observations: 1) while pixels may change rapidly from frame to frame, the semantic content of a scene evolves more slowly, and 2) execution can be viewed as an aspect of architecture, yielding purpose-fit computation schedules for networks. We define a novel family of "clockwork" convnets driven by fixed or adaptive clock signals that schedule the processing of different layers at different update rates according to their semantic stability. We design a pipeline schedule to reduce latency for real-time recognition and a fixed-rate schedule to reduce overall computation. Finally, we extend clockwork scheduling to adaptive video processing by incorporating data-driven clocks that can be tuned on unlabeled video. The accuracy and efficiency of clockwork convnets are evaluated on the Youtube-Objects, NYUD, and Cityscapes video datasets.

##### Abstract (translated by Google)
近年来静止图像分割取得了巨大的进展，然而，将这些最先进的算法应用到每个视频帧需要大量的计算，而忽略了视频固有的时间连续性，我们提出了一个视频识别框架，它依赖于两个关键的观察：1）像素一个场景的语义内容变化较慢，2）执行可以被看作是体系结构的一个方面，为网络产生适合目标的计算调度，我们定义了一个新的“发条”由固定或自适应时钟信号驱动，根据语义的稳定性，以不同的更新速率对不同层次的处理进行调度;设计一个流水线时间表来减少实时识别的延迟和固定速率的时间表来减少整体计算;我们将发条调度扩展到自适应视频处理，将数据驱动的时钟合并到未标记的视频中。在Youtube-Objects，NYUD和Cityscapes视频数据集上评估Ork的边框。

##### URL
[https://arxiv.org/abs/1608.03609](https://arxiv.org/abs/1608.03609)

##### PDF
[https://arxiv.org/pdf/1608.03609](https://arxiv.org/pdf/1608.03609)

