---
layout: post
title: "NegPSpan: efficient extraction of negative sequential patterns with embedding constraints"
date: 2018-07-25 13:42:47
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Thomas Guyet (LACODAM), Ren&#xe9; Quiniou (LACODAM)
mathjax: true
---

* content
{:toc}

##### Abstract
Mining frequent sequential patterns consists in extracting recurrent behaviors, modeled as patterns, in a big sequence dataset. Such patterns inform about which events are frequently observed in sequences, i.e. what does really happen. Sometimes, knowing that some specific event does not happen is more informative than extracting a lot of observed events. Negative sequential patterns (NSP) formulate recurrent behaviors by patterns containing both observed events and absent events. Few approaches have been proposed to mine such NSPs. In addition, the syntax and semantics of NSPs differ in the different methods which makes it difficult to compare them. This article provides a unified framework for the formulation of the syntax and the semantics of NSPs. Then, we introduce a new algorithm, NegPSpan, that extracts NSPs using a PrefixSpan depth-first scheme and enabling maxgap constraints that other approaches do not take into account. The formal framework allows for highlighting the differences between the proposed approach wrt to the methods from the literature, especially wrt the state of the art approach eNSP. Intensive experiments on synthetic and real datasets show that NegPSpan can extract meaningful NSPs and that it can process bigger datasets than eNSP thanks to significantly lower memory requirements and better computation times.

##### Abstract (translated by Google)
挖掘频繁的序列模式包括在大序列数据集中提取模型化的复现行为。这些模式告知在序列中经常观察到哪些事件，即实际发生了什么。有时，知道某些特定事件不会发生比提取大量观察到的事件更具信息性。负序列模式（NSP）通过包含观察事件和缺席事件的模式来制定反复行为。很少有人提出采用这种NSP的方法。此外，NSP的语法和语义在不同方法上有所不同，这使得难以对它们进行比较。本文为NSP的语法和语义的制定提供了统一的框架。然后，我们引入了一种新算法NegPSpan，它使用PrefixSpan深度优先方案提取NSP，并启用其他方法不考虑的maxgap约束。正式框架允许强调所提出的方法与文献中的方法之间的差异，尤其是现有技术方法eNSP。对合成和真实数据集的密集实验表明，NegPSpan可以提取有意义的NSP，并且由于显着降低了内存需求和更好的计算时间，它可以处理比eNSP更大的数据集。

##### URL
[http://arxiv.org/abs/1804.01256](http://arxiv.org/abs/1804.01256)

##### PDF
[http://arxiv.org/pdf/1804.01256](http://arxiv.org/pdf/1804.01256)

