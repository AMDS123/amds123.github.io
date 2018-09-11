---
layout: post
title: "Simplified Hierarchical Recurrent Encoder-Decoder for Building End-To-End Dialogue Systems"
date: 2018-09-08 11:54:09
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Chao Wang, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
As a generative model for building end-to-end dialogue systems, Hierarchical Recurrent Encoder-Decoder (HRED) consists of three layers of Gated Recurrent Unit (GRU), which from bottom to top are separately used as the word-level encoder, the sentence-level encoder, and the decoder. Despite performing well on dialogue corpora, HRED is computationally expensive to train due to its complexity. To improve the training efficiency of HRED, we propose a new model, which is named as Simplified HRED (SHRED), by making each layer of HRED except the top one simpler than its upper layer. On the one hand, we propose Scalar Gated Unit (SGU), which is a simplified variant of GRU, and use it as the sentence-level encoder. On the other hand, we use Fixed-size Ordinally-Forgetting Encoding (FOFE), which has no trainable parameter at all, as the word-level encoder. The experimental results show that compared with HRED under the same word embedding size and the same hidden state size for each layer, SHRED reduces the number of trainable parameters by 25\%--35\%, and the training time by more than 50\%, but still achieves slightly better performance.

##### Abstract (translated by Google)
作为构建端到端对话系统的生成模型，分层递归编码器 - 解码器（HRED）由三层门控递归单元（GRU）组成，从底部到顶部分别用作字级编码器，句码级编码器和解码器。尽管在对话语料库上表现良好，但由于其复杂性，HRED的计算成本很高。为了提高HRED的训练效率，我们提出了一种新模型，称为简化HRED（SHRED），通过使除了顶层之外的每层HRED比其上层更简单。一方面，我们提出标量门控单元（SGU），它是GRU的简化变体，并将其用作句子级编码器。另一方面，我们使用固定大小的普通遗忘编码（FOFE）作为字级编码器，它根本没有可训练的参数。实验结果表明，与相同单词嵌入大小和每层相同隐藏状态大小的HRED相比，SHRED将可训练参数的数量减少了25％~35％，训练时间减少了50％以上。 ％，但仍然可以实现稍微好一点的性能。

##### URL
[http://arxiv.org/abs/1809.02790](http://arxiv.org/abs/1809.02790)

##### PDF
[http://arxiv.org/pdf/1809.02790](http://arxiv.org/pdf/1809.02790)

