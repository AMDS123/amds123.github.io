---
layout: post
title: "Gram-CTC: Automatic Unit Selection and Target Decomposition for Sequence Labelling"
date: 2017-08-12 00:02:26
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Hairong Liu, Zhenyao Zhu, Xiangang Li, Sanjeev Satheesh
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing sequence labelling models rely on a fixed decomposition of a target sequence into a sequence of basic units. These methods suffer from two major drawbacks: 1) the set of basic units is fixed, such as the set of words, characters or phonemes in speech recognition, and 2) the decomposition of target sequences is fixed. These drawbacks usually result in sub-optimal performance of modeling sequences. In this pa- per, we extend the popular CTC loss criterion to alleviate these limitations, and propose a new loss function called Gram-CTC. While preserving the advantages of CTC, Gram-CTC automatically learns the best set of basic units (grams), as well as the most suitable decomposition of tar- get sequences. Unlike CTC, Gram-CTC allows the model to output variable number of characters at each time step, which enables the model to capture longer term dependency and improves the computational efficiency. We demonstrate that the proposed Gram-CTC improves CTC in terms of both performance and efficiency on the large vocabulary speech recognition task at multiple scales of data, and that with Gram-CTC we can outperform the state-of-the-art on a standard speech benchmark.

##### Abstract (translated by Google)
大多数现有的序列标签模型依赖于将目标序列固定分解成一系列基本单元。这些方法存在两大缺点：1）基本单位集是固定的，如语音识别中的单词，字符或音素集; 2）目标序列的分解是固定的。这些缺点通常导致建模序列的次优性能。在本文中，我们扩展了流行的CTC损失标准来缓解这些限制，并提出了一种新的称为Gram-CTC的损失函数。在保留CTC优势的同时，Gram-CTC能够自动学习最佳的基本单位（克），以及最适合的目标分解序列。与CTC不同的是，Gram-CTC允许模型在每个时间步输出可变数量的字符，这使得模型能够获得更长期的依赖性并提高计算效率。我们证明了所提出的Gram-CTC在数据的多个尺度上在大的词汇表语音识别任务上的性能和效率方面提高了CTC，并且使用Gram-CTC我们可以超越标准的现状演讲基准。

##### URL
[https://arxiv.org/abs/1703.00096](https://arxiv.org/abs/1703.00096)

##### PDF
[https://arxiv.org/pdf/1703.00096](https://arxiv.org/pdf/1703.00096)

