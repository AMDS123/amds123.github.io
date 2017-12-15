---
layout: post
title: "Anchor-Free Correlated Topic Modeling: Identifiability and Algorithm"
date: 2016-11-15 20:06:40
categories: arXiv_CL
tags: arXiv_CL
author: Kejun Huang, Xiao Fu, Nicholas D. Sidiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
In topic modeling, many algorithms that guarantee identifiability of the topics have been developed under the premise that there exist anchor words -- i.e., words that only appear (with positive probability) in one topic. Follow-up work has resorted to three or higher-order statistics of the data corpus to relax the anchor word assumption. Reliable estimates of higher-order statistics are hard to obtain, however, and the identification of topics under those models hinges on uncorrelatedness of the topics, which can be unrealistic. This paper revisits topic modeling based on second-order moments, and proposes an anchor-free topic mining framework. The proposed approach guarantees the identification of the topics under a much milder condition compared to the anchor-word assumption, thereby exhibiting much better robustness in practice. The associated algorithm only involves one eigen-decomposition and a few small linear programs. This makes it easy to implement and scale up to very large problem instances. Experiments using the TDT2 and Reuters-21578 corpus demonstrate that the proposed anchor-free approach exhibits very favorable performance (measured using coherence, similarity count, and clustering accuracy metrics) compared to the prior art.

##### Abstract (translated by Google)
在话题建模中，许多保证主题可识别性的算法都是在存在锚定词的前提下发展起来的，即在一个话题中只出现（具有正概率）的词。后续工作利用数据语料库的三个或更多的统计量来放宽锚词假设。然而，对高阶统计量的可靠估计是难以获得的，而在这些模型下确定话题取决于话题的不相关性，这可能是不现实的。本文重新讨论了基于二阶矩的主题建模，并提出了一种无锚点的主题挖掘框架。与锚词假设相比，所提出的方法保证在更温和的条件下识别话题，从而在实践中表现出更好的鲁棒性。相关的算法只涉及一个特征分解和一些小的线性程序。这使得易于实现和扩展到非常大的问题实例。使用TDT2和Reuters-21578语料库的实验表明，与现有技术相比，所提出的无锚方法表现出非常有利的性能（使用一致性，相似性计数和聚类准确性度量来测量）。

##### URL
[https://arxiv.org/abs/1611.05010](https://arxiv.org/abs/1611.05010)

##### PDF
[https://arxiv.org/pdf/1611.05010](https://arxiv.org/pdf/1611.05010)

