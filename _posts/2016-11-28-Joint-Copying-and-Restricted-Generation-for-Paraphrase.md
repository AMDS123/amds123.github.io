---
layout: post
title: "Joint Copying and Restricted Generation for Paraphrase"
date: 2016-11-28 16:49:37
categories: arXiv_CL
tags: arXiv_CL Attention Summarization
author: Ziqiang Cao, Chuwei Luo, Wenjie Li, Sujian Li
mathjax: true
---

* content
{:toc}

##### Abstract
Many natural language generation tasks, such as abstractive summarization and text simplification, are paraphrase-orientated. In these tasks, copying and rewriting are two main writing modes. Most previous sequence-to-sequence (Seq2Seq) models use a single decoder and neglect this fact. In this paper, we develop a novel Seq2Seq model to fuse a copying decoder and a restricted generative decoder. The copying decoder finds the position to be copied based on a typical attention model. The generative decoder produces words limited in the source-specific vocabulary. To combine the two decoders and determine the final output, we develop a predictor to predict the mode of copying or rewriting. This predictor can be guided by the actual writing mode in the training data. We conduct extensive experiments on two different paraphrase datasets. The result shows that our model outperforms the state-of-the-art approaches in terms of both informativeness and language quality.

##### Abstract (translated by Google)
许多自然语言生成任务，如抽象概括和文本简化，都是以复述为导向的。在这些任务中，复制和重写是两种主要的写作模式。大多数先前的序列到序列（Seq2Seq）模型使用单个解码器并忽略这个事实。在本文中，我们开发了一种新的Seq2Seq模型来融合复制解码器和受限的生成解码器。复制解码器根据典型的关注模型找到要复制的位置。生成的解码器生成限定在源特定词汇表中的单词。为了组合两个解码器并确定最终输出，我们开发了一个预测器来预测复制或重写的模式。这个预测指标可以通过训练数据中的实际写作模式来指导。我们对两个不同的释义数据集进行了广泛的实验。结果表明，我们的模型在信息性和语言质量方面都优于最新的方法。

##### URL
[https://arxiv.org/abs/1611.09235](https://arxiv.org/abs/1611.09235)

##### PDF
[https://arxiv.org/pdf/1611.09235](https://arxiv.org/pdf/1611.09235)

