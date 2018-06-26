---
layout: post
title: "Prior Attention for Style-aware Sequence-to-Sequence Models"
date: 2018-06-25 13:17:24
categories: arXiv_CL
tags: arXiv_CL Attention
author: Lucas Sterckx, Johannes Deleu, Chris Develder, Thomas Demeester
mathjax: true
---

* content
{:toc}

##### Abstract
We extend sequence-to-sequence models with the possibility to control the characteristics or style of the generated output, via attention that is generated a priori (before decoding) from a latent code vector. After training an initial attention-based sequence-to-sequence model, we use a variational auto-encoder conditioned on representations of input sequences and a latent code vector space to generate attention matrices. By sampling the code vector from specific regions of this latent space during decoding and imposing prior attention generated from it in the seq2seq model, output can be steered towards having certain attributes. This is demonstrated for the task of sentence simplification, where the latent code vector allows control over output length and lexical simplification, and enables fine-tuning to optimize for different evaluation metrics.

##### Abstract (translated by Google)
我们扩展序列到序列模型，通过潜在代码向量的先验（解码之前）产生的注意力来控制生成输出的特征或风格。在训练了一个初始的基于注意力的序列到序列模型之后，我们使用一个变分自动编码器，以输入序列和潜在代码向量空间的表示为条件来产生注意矩阵。通过在解码期间从该潜在空间的特定区域对代码向量进行采样，并且在seq2seq模型中对其产生事先关注，可以将输出引导至具有某些属性。这对于句子简化的任务来说明，其中潜在的代码向量允许控制输出长度和词汇简化，并且允许微调优化以用于不同的评估度量。

##### URL
[http://arxiv.org/abs/1806.09439](http://arxiv.org/abs/1806.09439)

##### PDF
[http://arxiv.org/pdf/1806.09439](http://arxiv.org/pdf/1806.09439)

