---
layout: post
title: "Character-Level Language Modeling with Deeper Self-Attention"
date: 2018-08-09 18:44:38
categories: arXiv_AI
tags: arXiv_AI Attention RNN Language_Model
author: Rami Al-Rfou, Dokook Choe, Noah Constant, Mandy Guo, Llion Jones
mathjax: true
---

* content
{:toc}

##### Abstract
LSTMs and other RNN variants have shown strong performance on character-level language modeling. These models are typically trained using truncated backpropagation through time, and it is common to assume that their success stems from their ability to remember long-term contexts. In this paper, we show that a deep (64-layer) transformer model with fixed context outperforms RNN variants by a large margin, achieving state of the art on two popular benchmarks- 1.13 bits per character on text8 and 1.06 on enwik8. To get good results at this depth, we show that it is important to add auxiliary losses, both at intermediate network layers and intermediate sequence positions.

##### Abstract (translated by Google)
LSTM和其他RNN变体在字符级语言建模方面表现出强大的表现。这些模型通常使用截断的反向传播进行训练，并且通常认为它们的成功源于它们记住长期背景的能力。在本文中，我们展示了具有固定上下文的深（64层）变换器模型大大优于RNN变体，在两个流行的基准测试中实现了最先进的技术 - 在text8上每个字符1.13位，在enwik8上为1.06。为了在这个深度获得良好的结果，我们表明在中间网络层和中间序列位置添加辅助损失是很重要的。

##### URL
[http://arxiv.org/abs/1808.04444](http://arxiv.org/abs/1808.04444)

##### PDF
[http://arxiv.org/pdf/1808.04444](http://arxiv.org/pdf/1808.04444)

