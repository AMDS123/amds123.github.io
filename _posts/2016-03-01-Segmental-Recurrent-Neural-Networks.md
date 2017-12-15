---
layout: post
title: "Segmental Recurrent Neural Networks"
date: 2016-03-01 22:46:37
categories: arXiv_CL
tags: arXiv_CL Segmentation Embedding RNN Classification Recognition
author: Lingpeng Kong, Chris Dyer, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce segmental recurrent neural networks (SRNNs) which define, given an input sequence, a joint probability distribution over segmentations of the input and labelings of the segments. Representations of the input segments (i.e., contiguous subsequences of the input) are computed by encoding their constituent tokens using bidirectional recurrent neural nets, and these "segment embeddings" are used to define compatibility scores with output labels. These local compatibility scores are integrated using a global semi-Markov conditional random field. Both fully supervised training -- in which segment boundaries and labels are observed -- as well as partially supervised training -- in which segment boundaries are latent -- are straightforward. Experiments on handwriting recognition and joint Chinese word segmentation/POS tagging show that, compared to models that do not explicitly represent segments such as BIO tagging schemes and connectionist temporal classification (CTC), SRNNs obtain substantially higher accuracies.

##### Abstract (translated by Google)
我们引入节段性递归神经网络（SRNN），其给定输入序列中输入和标记段的分段上的联合概率分布。输入段（即输入的连续子序列）的表示通过使用双向递归神经网络对其组成标记进行编码来计算，并且这些“段嵌入”用于定义与输出标签的兼容性分数。这些局部兼容性分数使用全局半马尔可夫条件随机场进行整合。完全监督的训练 - 在这个训练中，观察分界线和标签 - 以及部分监督的训练 - 在这个分界线是潜在的 - 是直截了当的。手写识别和联合中文分词/词性标注的实验表明，与未明确表示节段的模型（如BIO标签方案和联结主义时间分类（CTC））相比，SRNN获得了更高的精度。

##### URL
[https://arxiv.org/abs/1511.06018](https://arxiv.org/abs/1511.06018)

##### PDF
[https://arxiv.org/pdf/1511.06018](https://arxiv.org/pdf/1511.06018)

