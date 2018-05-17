---
layout: post
title: "Composing Finite State Transducers on GPUs"
date: 2018-05-16 15:56:17
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Speech_Recognition Optimization Recognition
author: Arturo Argueta, David Chiang
mathjax: true
---

* content
{:toc}

##### Abstract
Weighted finite-state transducers (FSTs) are frequently used in language processing to handle tasks such as part-of-speech tagging and speech recognition. There has been previous work using multiple CPU cores to accelerate finite state algorithms, but limited attention has been given to parallel graphics processing unit (GPU) implementations. In this paper, we introduce the first (to our knowledge) GPU implementation of the FST composition operation, and we also discuss the optimizations used to achieve the best performance on this architecture. We show that our approach obtains speedups of up to 6x over our serial implementation and 4.5x over OpenFST.

##### Abstract (translated by Google)
加权有限状态转换器（FST）经常用于语言处理以处理诸如词性标注和语音识别之类的任务。以前的工作使用多个CPU内核来加速有限状态算法，但是并行图形处理单元（GPU）实现却受到了有限的关注。在本文中，我们介绍了第一个（据我们所知）FST合成操作的GPU实现，并且我们还讨论了用于在此架构上实现最佳性能的优化。我们展示了我们的方法在我们的串行实现方面获得高达6倍的加速，在OpenFST方面获得4.5倍的加速。

##### URL
[http://arxiv.org/abs/1805.06383](http://arxiv.org/abs/1805.06383)

##### PDF
[http://arxiv.org/pdf/1805.06383](http://arxiv.org/pdf/1805.06383)

