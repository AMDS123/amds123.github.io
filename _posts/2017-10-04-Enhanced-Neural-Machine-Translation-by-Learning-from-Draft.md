---
layout: post
title: "Enhanced Neural Machine Translation by Learning from Draft"
date: 2017-10-04 20:13:43
categories: arXiv_CL
tags: arXiv_CL NMT
author: Aodong Li, Shiyue Zhang, Dong Wang, Thomas Fang Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has recently achieved impressive results. A potential problem of the existing NMT algorithm, however, is that the decoding is conducted from left to right, without considering the right context. This paper proposes an two-stage approach to solve the problem. In the first stage, a conventional attention-based NMT system is used to produce a draft translation, and in the second stage, a novel double-attention NMT system is used to refine the translation, by looking at the original input as well as the draft translation. This drafting-and-refinement can obtain the right-context information from the draft, hence producing more consistent translations. We evaluated this approach using two Chinese-English translation tasks, one with 44k pairs and 1M pairs respectively. The experiments showed that our approach achieved positive improvements over the conventional NMT system: the improvements are 2.4 and 0.9 BLEU points on the small-scale and large-scale tasks, respectively.

##### Abstract (translated by Google)
神经机器翻译（NMT）最近取得了令人瞩目的成果。然而，现有的NMT算法的一个潜在的问题是解码是从左到右进行的，没有考虑正确的上下文。本文提出了一个两阶段的方法来解决这个问题。在第一阶段，传统的基于注意力的NMT系统被用来生成一个草稿翻译，在第二个阶段，一个新颖的双注意NMT系统被用来细化翻译，通过查看原始输入以及草稿翻译。这种起草和完善可以从草案中获得正确的背景信息，从而产生更一致的翻译。我们使用两个中英文翻译任务来评估这个方法，分别是44k对和1M对。实验表明，我们的方法比传统的NMT系统取得了积极的改进：小规模和大规模的任务分别提高了2.4和0.9 BLEU点。

##### URL
[https://arxiv.org/abs/1710.01789](https://arxiv.org/abs/1710.01789)

