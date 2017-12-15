---
layout: post
title: "An Empirical Study of Adequate Vision Span for Attention-Based Neural Machine Translation"
date: 2017-06-08 07:52:36
categories: arXiv_CL
tags: arXiv_CL Attention
author: Raphael Shu, Hideki Nakayama
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the attention mechanism plays a key role to achieve high performance for Neural Machine Translation models. However, as it computes a score function for the encoder states in all positions at each decoding step, the attention model greatly increases the computational complexity. In this paper, we investigate the adequate vision span of attention models in the context of machine translation, by proposing a novel attention framework that is capable of reducing redundant score computation dynamically. The term "vision span" means a window of the encoder states considered by the attention model in one step. In our experiments, we found that the average window size of vision span can be reduced by over 50% with modest loss in accuracy on English-Japanese and German-English translation tasks.% This results indicate that the conventional attention mechanism performs a significant amount of redundant computation.

##### Abstract (translated by Google)
最近，关注机制对于实现神经机器翻译模型的高性能起着关键作用。然而，由于它计算每个解码步骤中所有位置处的编码器状态的分数函数，所以关注模型大大增加了计算复杂度。在本文中，我们通过提出一个能够动态减少冗余分数计算的新型注意框架，来研究在机器翻译环境中注意模型的适当视觉跨度。术语“视觉范围”是指由注意模型一步考虑的编码器状态的窗口。在我们的实验中，我们发现英文日文和德文 - 英文翻译任务的平均窗口大小可以减少50％以上，并且准确度损失适中。这个结果表明传统的注意机制执行了大量的的冗余计算。

##### URL
[https://arxiv.org/abs/1612.06043](https://arxiv.org/abs/1612.06043)

##### PDF
[https://arxiv.org/pdf/1612.06043](https://arxiv.org/pdf/1612.06043)

