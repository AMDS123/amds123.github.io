---
layout: post
title: "Predicting Visual Context for Unsupervised Event Segmentation in Continuous Photo-streams"
date: 2018-08-07 10:03:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Summarization RNN
author: Ana Garcia del Molino, Joo-Hwee Lim, Ah-Hwee Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting video content into events provides semantic structures for indexing, retrieval, and summarization. Since motion cues are not available in continuous photo-streams, and annotations in lifelogging are scarce and costly, the frames are usually clustered into events by comparing the visual features between them in an unsupervised way. However, such methodologies are ineffective to deal with heterogeneous events, e.g. taking a walk, and temporary changes in the sight direction, e.g. at a meeting. To address these limitations, we propose Contextual Event Segmentation (CES), a novel segmentation paradigm that uses an LSTM-based generative network to model the photo-stream sequences, predict their visual context, and track their evolution. CES decides whether a frame is an event boundary by comparing the visual context generated from the frames in the past, to the visual context predicted from the future. We implemented CES on a new and massive lifelogging dataset consisting of more than 1.5 million images spanning over 1,723 days. Experiments on the popular EDUB-Seg dataset show that our model outperforms the state-of-the-art by over 16% in f-measure. Furthermore, CES' performance is only 3 points below that of human annotators.

##### Abstract (translated by Google)
将视频内容分段为事件为索引，检索和摘要提供了语义结构。由于运动提示在连续光流中不可用，并且生命日中的注释很少且成本高，因此通常通过以无人监督的方式比较它们之间的视觉特征来将帧聚类成事件。然而，这种方法对于处理异构事件是无效的，例如，散步，以及视线方向的临时变化，例如，在一次会议上。为了解决这些局限性，我们提出了上下文事件分割（CES），这是一种新的分割范例，它使用基于LSTM的生成网络对照片流序列进行建模，预测其视觉背景并跟踪其演化。 CES通过比较从过去的帧生成的视觉上下文到从未来预测的视觉上下文来确定帧是否是事件边界。我们在一个新的大型生命日志数据集上实施了CES，该数据集包含超过1,723天的150多万张图像。在流行的EDUB-Seg数据集上的实验表明，我们的模型在f-measure中的表现优于现有技术超过16％。此外，CES的表现仅比人类注释者低3分。

##### URL
[http://arxiv.org/abs/1808.02289](http://arxiv.org/abs/1808.02289)

##### PDF
[http://arxiv.org/pdf/1808.02289](http://arxiv.org/pdf/1808.02289)

