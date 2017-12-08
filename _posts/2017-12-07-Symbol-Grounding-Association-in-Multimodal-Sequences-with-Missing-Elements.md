---
layout: post
title: "Symbol Grounding Association in Multimodal Sequences with Missing Elements"
date: 2017-12-07 10:14:23
categories: arXiv_CV
tags: arXiv_CV RNN
author: Federico Raue, Andreas Dengel, Thomas M. Breuel, Marcus Liwicki
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we extend a symbolic association framework for being able to handle missing elements in multimodal sequences. The general scope of the work is the symbolic associations of object-word mappings as it happens in language development in infants. In other words, two different representations of the same abstract concepts can associate in both directions. This scenario has been long interested in Artificial Intelligence, Psychology, and Neuroscience. In this work, we extend a recent approach for multimodal sequences (visual and audio) to also cope with missing elements in one or both modalities. Our method uses two parallel Long Short-Term Memories (LSTMs) with a learning rule based on EM-algorithm. It aligns both LSTM outputs via Dynamic Time Warping (DTW). We propose to include an extra step for the combination with the max operation for exploiting the common elements between both sequences. The motivation behind is that the combination acts as a condition selector for choosing the best representation from both LSTMs. We evaluated the proposed extension in the following scenarios: missing elements in one modality (visual or audio) and missing elements in both modalities (visual and sound). The performance of our extension reaches better results than the original model and similar results to individual LSTM trained in each modality.

##### Abstract (translated by Google)
在本文中，我们扩展了能够处理多模式序列中缺失元素的符号关联框架。作品的一般范围是在婴儿的语言发展中发生的对象词映射的象征关联。换句话说，相同抽象概念的两种不同表示可以在两个方向上相关联。这种情况一直对人工智能，心理学和神经科学感兴趣。在这项工作中，我们扩展了最近的多模式序列（视觉和音频）方法，以处理一个或两个模式中缺失的元素。我们的方法使用了基于EM算法的两个并行的长时短暂存储器（LSTM）和一个学习规则。它通过动态时间规整（DTW）对齐两个LSTM输出。我们建议包括一个额外的步骤与最大操作的组合，以利用两个序列之间的公共元素。背后的动机是组合作为一个条件选择器从两个LSTM中选择最佳表示。我们在以下情况下评估了提议的扩展：在一种模式（视觉或音频）中缺少元素，在两种模式（视觉和声音）中缺少元素。我们扩展的性能比原始模型达到更好的结果，并且在每种模式下培训的单个LSTM的结果类似。

##### URL
[http://arxiv.org/abs/1511.04401](http://arxiv.org/abs/1511.04401)

##### PDF
[http://arxiv.org/pdf/1511.04401](http://arxiv.org/pdf/1511.04401)

