---
layout: post
title: "Language Modeling with Gated Convolutional Networks"
date: 2017-09-08 22:26:49
categories: arXiv_CL
tags: arXiv_CL Knowledge CNN RNN Language_Model
author: Yann N. Dauphin, Angela Fan, Michael Auli, David Grangier
mathjax: true
---

* content
{:toc}

##### Abstract
The pre-dominant approach to language modeling to date is based on recurrent neural networks. Their success on this task is often linked to their ability to capture unbounded context. In this paper we develop a finite context approach through stacked convolutions, which can be more efficient since they allow parallelization over sequential tokens. We propose a novel simplified gating mechanism that outperforms Oord et al (2016) and investigate the impact of key architectural decisions. The proposed approach achieves state-of-the-art on the WikiText-103 benchmark, even though it features long-term dependencies, as well as competitive results on the Google Billion Words benchmark. Our model reduces the latency to score a sentence by an order of magnitude compared to a recurrent baseline. To our knowledge, this is the first time a non-recurrent approach is competitive with strong recurrent models on these large scale language tasks.

##### Abstract (translated by Google)
迄今为止，语言建模的主导方法是基于递归神经网络。他们在这个任务上的成功往往与他们捕捉无限背景的能力有关。在本文中，我们通过堆叠卷积来开发有限上下文方法，由于它们允许并行化顺序令牌，所以可以更高效。我们提出了一种新的简化的门控机制，胜过Oord等（2016），并调查关键架构决策的影响。所提出的方法在WikiText-103基准测试中达到了最新的水平，尽管它具有长期依赖性，并且在Google Billion Words基准测试中具有竞争性的结果。与复发基线相比，我们的模型将句子的潜伏期缩短了一个数量级。据我们所知，这是非经常性的方法首次与这些大规模语言任务的强循环模型相竞争。

##### URL
[https://arxiv.org/abs/1612.08083](https://arxiv.org/abs/1612.08083)

##### PDF
[https://arxiv.org/pdf/1612.08083](https://arxiv.org/pdf/1612.08083)

