---
layout: post
title: "Plan, Attend, Generate: Character-level Neural Machine Translation with Planning in the Decoder"
date: 2017-06-23 06:31:05
categories: arXiv_CL
tags: arXiv_CL
author: Caglar Gulcehre, Francis Dutil, Adam Trischler, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the integration of a planning mechanism into an encoder-decoder architecture with an explicit alignment for character-level machine translation. We develop a model that plans ahead when it computes alignments between the source and target sequences, constructing a matrix of proposed future alignments and a commitment vector that governs whether to follow or recompute the plan. This mechanism is inspired by the strategic attentive reader and writer (STRAW) model. Our proposed model is end-to-end trainable with fully differentiable operations. We show that it outperforms a strong baseline on three character-level decoder neural machine translation on WMT'15 corpus. Our analysis demonstrates that our model can compute qualitatively intuitive alignments and achieves superior performance with fewer parameters.

##### Abstract (translated by Google)
我们调查了规划机制与编码器 - 解码器体系结构的整合，以及字符级机器翻译的明确对齐。当计算源序列和目标序列之间的比对时，我们开发了一个计划模型，构建一个提议的未来比对矩阵和一个管理是否遵循或重新计划该计划的承诺向量。这种机制受到战略性的细心读者和作者（STRAW）模式的启发。我们提出的模型是端到端的可训练的完全可微操作。我们发现，它在WMT'15语料库上的三个字符级解码器神经机器翻译性能优于强基线。我们的分析表明，我们的模型可以计算定性直观的对齐，并以较少的参数实现卓越的性能。

##### URL
[https://arxiv.org/abs/1706.05087](https://arxiv.org/abs/1706.05087)

##### PDF
[https://arxiv.org/pdf/1706.05087](https://arxiv.org/pdf/1706.05087)

