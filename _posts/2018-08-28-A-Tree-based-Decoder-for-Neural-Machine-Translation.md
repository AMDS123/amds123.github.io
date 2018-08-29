---
layout: post
title: "A Tree-based Decoder for Neural Machine Translation"
date: 2018-08-28 15:52:19
categories: arXiv_CL
tags: arXiv_CL Knowledge NMT RNN
author: Xinyi Wang, Hieu Pham, Pengcheng Yin, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in Neural Machine Translation (NMT) show that adding syntactic information to NMT systems can improve the quality of their translations. Most existing work utilizes some specific types of linguistically-inspired tree structures, like constituency and dependency parse trees. This is often done via a standard RNN decoder that operates on a linearized target tree structure. However, it is an open question of what specific linguistic formalism, if any, is the best structural representation for NMT. In this paper, we (1) propose an NMT model that can naturally generate the topology of an arbitrary tree structure on the target side, and (2) experiment with various target tree structures. Our experiments show the surprising result that our model delivers the best improvements with balanced binary trees constructed without any linguistic knowledge; this model outperforms standard seq2seq models by up to 2.1 BLEU points, and other methods for incorporating target-side syntax by up to 0.7 BLEU.

##### Abstract (translated by Google)
神经机器翻译（NMT）的最新进展表明，向NMT系统添加句法信息可以提高翻译质量。大多数现有工作使用一些特定类型的语言启发树结构，如选区和依赖解析树。这通常通过在线性化目标树结构上操作的标准RNN解码器来完成。然而，对于NMT来说，具体的语言形式主义（如果有的话）是最好的结构表示是一个悬而未决的问题。在本文中，我们（1）提出了一种NMT模型，它可以自然地在目标端生成任意树结构的拓扑，以及（2）实验各种目标树结构。我们的实验表明，令人惊讶的结果是我们的模型在没有任何语言知识的情况下构建了平衡二叉树，从而实现了最佳改进该模型的性能优于标准的seq2seq模型，最高可达2.1 BLEU点，其他方法可将目标端语法合并至最高0.7 BLEU。

##### URL
[http://arxiv.org/abs/1808.09374](http://arxiv.org/abs/1808.09374)

##### PDF
[http://arxiv.org/pdf/1808.09374](http://arxiv.org/pdf/1808.09374)

