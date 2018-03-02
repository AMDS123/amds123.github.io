---
layout: post
title: "LSTM stack-based Neural Multi-sequence Alignment TeCHnique"
date: 2018-02-19 06:51:01
categories: arXiv_CV
tags: arXiv_CV RNN
author: Pelin Dogan, Boyang Li, Leonid Sigal, Markus Gross
mathjax: true
---

* content
{:toc}

##### Abstract
The alignment of heterogeneous sequential data (video to text) is an important and challenging problem. Standard techniques for such alignment, including Dynamic Time Warping (DTW) and Conditional Random Fields (CRFs), suffer from inherent drawbacks. Mainly, the Markov assumption implies that, given the immediate past, future alignment decisions are independent of further history. The separation between similarity computation and alignment decision also prevents end-to-end training. In this paper, we propose an end-to-end neural architecture where alignment actions are implemented as moving data between stacks of Long Short-term Memory (LSTM) blocks. This flexible architecture supports a large variety of alignment tasks, including one-to-one, one-to-many, skipping unmatched elements, and (with extensions) non-monotonic alignment. Extensive experiments on synthetic and real datasets show that our algorithm outperforms state-of-the-art baselines.

##### Abstract (translated by Google)
异构顺序数据（视频到文本）的对齐是一个重要和具有挑战性的问题。用于这种对齐的标准技术包括动态时间规整（DTW）和条件随机场（CRF），具有固有的缺点。主要的是，马尔可夫假设意味着，鉴于眼下的过去，未来的协调决定与历史进一步无关。相似性计算和对齐决策之间的分离也阻止了端到端的培训。在本文中，我们提出了一种端对端神经架构，其中对齐操作被实现为在长时间短内存（LSTM）块的堆栈之间移动数据。这种灵活的架构支持各种对齐任务，包括一对一，一对多，跳过不匹配的元素，以及（带扩展名）非单调对齐。对合成和实际数据集的大量实验表明，我们的算法优于最先进的基线。

##### URL
[http://arxiv.org/abs/1803.00057](http://arxiv.org/abs/1803.00057)

##### PDF
[http://arxiv.org/pdf/1803.00057](http://arxiv.org/pdf/1803.00057)

