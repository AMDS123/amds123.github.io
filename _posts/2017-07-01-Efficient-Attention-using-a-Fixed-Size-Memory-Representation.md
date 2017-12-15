---
layout: post
title: "Efficient Attention using a Fixed-Size Memory Representation"
date: 2017-07-01 08:16:24
categories: arXiv_CL
tags: arXiv_CL Attention Inference
author: Denny Britz, Melody Y. Guan, Minh-Thang Luong
mathjax: true
---

* content
{:toc}

##### Abstract
The standard content-based attention mechanism typically used in sequence-to-sequence models is computationally expensive as it requires the comparison of large encoder and decoder states at each time step. In this work, we propose an alternative attention mechanism based on a fixed size memory representation that is more efficient. Our technique predicts a compact set of K attention contexts during encoding and lets the decoder compute an efficient lookup that does not need to consult the memory. We show that our approach performs on-par with the standard attention mechanism while yielding inference speedups of 20% for real-world translation tasks and more for tasks with longer sequences. By visualizing attention scores we demonstrate that our models learn distinct, meaningful alignments.

##### Abstract (translated by Google)
通常在序列到序列模型中使用的标准的基于内容的关注机制在计算上是昂贵的，因为它需要在每个时间步骤比较大的编码器和解码器状态。在这项工作中，我们提出了一种基于固定大小的内存表示的替代关注机制，它更高效。我们的技术在编码过程中预测了一组紧凑的K注意上下文，并让解码器计算一个无需查阅内存的高效查找。我们展示了我们的方法与标准的关注机制相媲美，同时为真实世界的翻译任务产生20％的推理加速，而更多的序列更长的任务。通过对关注分数进行可视化，我们证明了我们的模型学习了独特而有意义的对齐

##### URL
[https://arxiv.org/abs/1707.00110](https://arxiv.org/abs/1707.00110)

##### PDF
[https://arxiv.org/pdf/1707.00110](https://arxiv.org/pdf/1707.00110)

