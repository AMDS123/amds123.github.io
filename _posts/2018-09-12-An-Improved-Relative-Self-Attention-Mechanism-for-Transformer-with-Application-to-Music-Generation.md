---
layout: post
title: "An Improved Relative Self-Attention Mechanism for Transformer with Application to Music Generation"
date: 2018-09-12 07:15:26
categories: arXiv_SD
tags: arXiv_SD Attention Relation
author: Cheng-Zhi Anna Huang, Ashish Vaswani, Jakob Uszkoreit, Noam Shazeer, Curtis Hawthorne, Andrew M. Dai, Matthew D. Hoffman, Douglas Eck
mathjax: true
---

* content
{:toc}

##### Abstract
Music relies heavily on self-reference to build structure and meaning. We explore the Transformer architecture (Vaswani et al., 2017) as a generative model for music, as self-attention has shown compelling results on tasks that require long-term structure such as Wikipedia summary generation (Liu et al, 2018). However, timing information is critical for polyphonic music, and Transformer does not explicitly model absolute or relative timing in its structure. To address this challenge, Shaw et al. (2018) introduced relative position representations to self-attention to improve machine translation. However, the formulation was not scalable to longer sequences. We propose an improved formulation which reduces the memory requirements of the relative position computation from $O(l^2d)$ to $O(ld)$, making it possible to train much longer sequences and achieve faster convergence. In experiments on symbolic music we find that relative self-attention substantially improves sample quality for unconditioned generation and is able to generate sequences of lengths longer than those from the training set. When primed with an initial sequence, the model generates continuations that develop the prime coherently and exhibit long-term structure. Relative self-attention can be instrumental in capturing richer relationships within a musical piece.

##### Abstract (translated by Google)
音乐在很大程度上依赖于自我引用来构建结构和意义。我们探索Transformer架构（Vaswani et al。，2017）作为音乐的生成模型，因为自我关注已经在需要长期结构的任务上显示出令人信服的结果，例如维基百科摘要生成（Liu et al，2018）。但是，时序信息对于复音音乐至关重要，而Transformer并未明确地对其结构中的绝对或相对时序进行建模。为了应对这一挑战，Shaw等人。 （2018）介绍了相对位置表示自我关注以改善机器翻译。然而，该配方不能扩展到更长的序列。我们提出了一种改进的公式，它将相对位置计算的内存需求从$ O（l ^ 2d）$减少到$ O（ld）$，从而可以训练更长的序列并实现更快的收敛。在符号音乐的实验中，我们发现相对自我关注大大提高了无条件生成的样本质量，并且能够生成比训练集中的长度更长的序列。当用初始序列引发时，该模型产生连续性，其连贯地形成素数并表现出长期结构。相对的自我关注可以有助于捕捉音乐作品中更丰富的关系。

##### URL
[http://arxiv.org/abs/1809.04281](http://arxiv.org/abs/1809.04281)

##### PDF
[http://arxiv.org/pdf/1809.04281](http://arxiv.org/pdf/1809.04281)

