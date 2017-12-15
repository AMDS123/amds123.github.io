---
layout: post
title: "Sequence-to-Sequence Learning as Beam-Search Optimization"
date: 2016-11-10 03:45:30
categories: arXiv_CL
tags: arXiv_CL Attention Optimization Language_Model
author: Sam Wiseman, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-Sequence (seq2seq) modeling has rapidly become an important general-purpose NLP tool that has proven effective for many text-generation and sequence-labeling tasks. Seq2seq builds on deep neural language modeling and inherits its remarkable accuracy in estimating local, next-word distributions. In this work, we introduce a model and beam-search training scheme, based on the work of Daume III and Marcu (2005), that extends seq2seq to learn global sequence scores. This structured approach avoids classical biases associated with local training and unifies the training loss with the test-time usage, while preserving the proven model architecture of seq2seq and its efficient training approach. We show that our system outperforms a highly-optimized attention-based seq2seq system and other baselines on three different sequence to sequence tasks: word ordering, parsing, and machine translation.

##### Abstract (translated by Google)
序列到序列（seq2seq）建模已经迅速成为一个重要的通用NLP工具，已被证明是有效的许多文本生成和序列标签任务。 Seq2seq以深度神经语言建模为基础，在估计本地，下一个字的分布方面继承了其卓越的准确性。在这项工作中，我们根据Daume III和Marcu（2005）的工作，引入了一个模型和波束搜索训练方案，该方案扩展了seq2seq来学习全局序列分数。这种结构化方法避免了与本地培训相关的经典偏差，并将培训损失与测试时间使用相结合，同时保留了seq2seq的经过验证的模型架构及其有效的培训方法。我们表明，我们的系统胜过了高度优化的基于注意力的seq2seq系统和其他三个不同顺序的基线来排序任务：词序，解析和机器翻译。

##### URL
[https://arxiv.org/abs/1606.02960](https://arxiv.org/abs/1606.02960)

##### PDF
[https://arxiv.org/pdf/1606.02960](https://arxiv.org/pdf/1606.02960)

