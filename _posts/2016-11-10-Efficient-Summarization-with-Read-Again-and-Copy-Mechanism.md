---
layout: post
title: "Efficient Summarization with Read-Again and Copy Mechanism"
date: 2016-11-10 16:23:04
categories: arXiv_CL
tags: arXiv_CL Summarization Prediction
author: Wenyuan Zeng, Wenjie Luo, Sanja Fidler, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder models have been widely used to solve sequence to sequence prediction tasks. However current approaches suffer from two shortcomings. First, the encoders compute a representation of each word taking into account only the history of the words it has read so far, yielding suboptimal representations. Second, current decoders utilize large vocabularies in order to minimize the problem of unknown words, resulting in slow decoding times. In this paper we address both shortcomings. Towards this goal, we first introduce a simple mechanism that first reads the input sequence before committing to a representation of each word. Furthermore, we propose a simple copy mechanism that is able to exploit very small vocabularies and handle out-of-vocabulary words. We demonstrate the effectiveness of our approach on the Gigaword dataset and DUC competition outperforming the state-of-the-art.

##### Abstract (translated by Google)
编码器 - 解码器模型已被广泛用于解序列预测任务。然而，目前的方法存在两个缺点。首先，编码器计算每个单词的表示，只考虑到目前为止已经阅读的单词的历史，产生次优表示。其次，当前的解码器使用大的词汇表来最小化未知单词的问题，导致解码时间较慢。在本文中，我们解决两个缺点。为了实现这个目标，我们首先引入一个简单的机制，在提交每个单词的表示之前首先读取输入序列。此外，我们提出了一个简单的复制机制，能够利用非常小的词汇表和处理词汇超出单词。我们在Gigaword数据集和DUC竞争中表现出我们的方法的有效性超越了最先进的技术。

##### URL
[https://arxiv.org/abs/1611.03382](https://arxiv.org/abs/1611.03382)

##### PDF
[https://arxiv.org/pdf/1611.03382](https://arxiv.org/pdf/1611.03382)

