---
layout: post
title: "Why is unsupervised alignment of English embeddings from different algorithms so hard?"
date: 2018-09-01 10:31:57
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Embedding Optimization
author: Mareike Hartmann, Yova Kementchedjhieva, Anders S&#xf8;gaard
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a challenge to the community: Generative adversarial networks (GANs) can perfectly align independent English word embeddings induced using the same algorithm, based on distributional information alone; but fails to do so, for two different embeddings algorithms. Why is that? We believe understanding why, is key to understand both modern word embedding algorithms and the limitations and instability dynamics of GANs. This paper shows that (a) in all these cases, where alignment fails, there exists a linear transform between the two embeddings (so algorithm biases do not lead to non-linear differences), and (b) similar effects can not easily be obtained by varying hyper-parameters. One plausible suggestion based on our initial experiments is that the differences in the inductive biases of the embedding algorithms lead to an optimization landscape that is riddled with local optima, leading to a very small basin of convergence, but we present this more as a challenge paper than a technical contribution.

##### Abstract (translated by Google)
本文向社区提出了一个挑战：生成对抗网络（GAN）可以完美地对齐使用相同算法诱导的独立英语单词嵌入，仅基于分布信息;但是没有这样做，对于两种不同的嵌入算法。这是为什么？我们相信理解为什么，理解现代单词嵌入算法和GAN的局限性和不稳定性动态是关键。本文表明（a）在所有这些情况下，在对齐失败的情况下，两个嵌入之间存在线性变换（因此算法偏差不会导致非线性差异），并且（b）不能轻易获得类似的效果通过改变超参数。基于我们最初实验的一个似是而非的建议是，嵌入算法的归纳偏差的差异导致了局部最优的优化环境，导致了非常小的收敛，但我们更多地将其作为挑战性文章提出而不是技术贡献。

##### URL
[http://arxiv.org/abs/1809.00150](http://arxiv.org/abs/1809.00150)

##### PDF
[http://arxiv.org/pdf/1809.00150](http://arxiv.org/pdf/1809.00150)

