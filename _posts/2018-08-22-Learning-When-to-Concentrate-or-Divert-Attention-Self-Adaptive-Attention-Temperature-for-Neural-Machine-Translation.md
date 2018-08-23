---
layout: post
title: "Learning When to Concentrate or Divert Attention: Self-Adaptive Attention Temperature for Neural Machine Translation"
date: 2018-08-22 14:13:24
categories: arXiv_AI
tags: arXiv_AI Attention NMT
author: Junyang Lin, Xu Sun, Xuancheng Ren, Muyu Li, Qi Su
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the Neural Machine Translation (NMT) models are based on the sequence-to-sequence (Seq2Seq) model with an encoder-decoder framework equipped with the attention mechanism. However, the conventional attention mechanism treats the decoding at each time step equally with the same matrix, which is problematic since the softness of the attention for different types of words (e.g. content words and function words) should differ. Therefore, we propose a new model with a mechanism called Self-Adaptive Control of Temperature (SACT) to control the softness of attention by means of an attention temperature. Experimental results on the Chinese-English translation and English-Vietnamese translation demonstrate that our model outperforms the baseline models, and the analysis and the case study show that our model can attend to the most relevant elements in the source-side contexts and generate the translation of high quality.

##### Abstract (translated by Google)
大多数神经机器翻译（NMT）模型基于序列到序列（Seq2Seq）模型，其具有配备有关注机制的编码器 - 解码器框架。然而，传统的注意机制在每个时间步骤上用相同的矩阵同等地处理解码，这是有问题的，因为不同类型的单词（例如内容单词和功能单词）的注意力的柔和性应该不同。因此，我们提出了一种新模型，其具有称为自适应温度控制（SACT）的机制，以通过注意温度来控制注意力的柔软性。汉英翻译和英越翻译的实验结果表明，我们的模型优于基线模型，分析和案例研究表明，我们的模型可以处理源侧背景中最相关的元素并生成翻译高品质。

##### URL
[http://arxiv.org/abs/1808.07374](http://arxiv.org/abs/1808.07374)

##### PDF
[http://arxiv.org/pdf/1808.07374](http://arxiv.org/pdf/1808.07374)

