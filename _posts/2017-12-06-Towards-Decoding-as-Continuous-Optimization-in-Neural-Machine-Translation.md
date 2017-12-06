---
layout: post
title: 'Towards Decoding as Continuous Optimization in Neural Machine Translation'
date: 2017-12-06 03:19:28
categories: arXiv_CL
tags: arXiv_CL NMT
author: Cong Duy Vu Hoang (University of Melbourne), Gholamreza Haffari (Monash University), Trevor Cohn (University of Melbourne)
---

* content
{:toc}

##### Abstract
We propose a novel decoding approach for neural machine translation (NMT) based on continuous optimisation. We convert decoding - basically a discrete optimization problem - into a continuous optimization problem. The resulting constrained continuous optimisation problem is then tackled using gradient-based methods. Our powerful decoding framework enables decoding intractable models such as the intersection of left-to-right and right-to-left (bidirectional) as well as source-to-target and target-to-source (bilingual) NMT models. Our empirical results show that our decoding framework is effective, and leads to substantial improvements in translations generated from the intersected models where the typical greedy or beam search is not feasible. We also compare our framework against reranking, and analyse its advantages and disadvantages.

##### Abstract (translated by Google)
我们提出了一种基于连续优化的神经机器翻译（NMT）的新颖解码方法。我们把解码 - 基本上是一个离散的优化问题 - 转换成一个连续优化问题。然后使用基于梯度的方法来解决由此产生的约束连续优化问题。我们强大的解码框架能够解码棘手的模型，例如从左到右和从右到左（双向）以及源到目标和目标到源（双语）NMT模型。我们的实证结果表明，我们的解码框架是有效的，并且导致从典型贪婪或束搜索不可行的相交模型产生的翻译的实质性改进。我们还将我们的框架与排序进行比较，分析其优缺点。

##### URL
[https://arxiv.org/abs/1701.02854](https://arxiv.org/abs/1701.02854)

