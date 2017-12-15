---
layout: post
title: "Parsing with Traces: An $O$ Algorithm and a Structural Representation"
date: 2017-07-13 16:52:08
categories: arXiv_CL
tags: arXiv_CL Inference
author: Jonathan K. Kummerfeld, Dan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
General treebank analyses are graph structured, but parsers are typically restricted to tree structures for efficiency and modeling reasons. We propose a new representation and algorithm for a class of graph structures that is flexible enough to cover almost all treebank structures, while still admitting efficient learning and inference. In particular, we consider directed, acyclic, one-endpoint-crossing graph structures, which cover most long-distance dislocation, shared argumentation, and similar tree-violating linguistic phenomena. We describe how to convert phrase structure parses, including traces, to our new representation in a reversible manner. Our dynamic program uniquely decomposes structures, is sound and complete, and covers 97.3% of the Penn English Treebank. We also implement a proof-of-concept parser that recovers a range of null elements and trace types.

##### Abstract (translated by Google)
一般的树库分析是图结构化的，但是为了效率和建模的原因，解析器通常限于树结构。我们为一类图结构提出了一种新的表示和算法，这种结构足够灵活，可以覆盖几乎所有的树型结构，同时仍然允许高效的学习和推理。具体而言，我们考虑了包含大多数长距离错位，共享论证和类似违树语言现象的有向非循环单终点交叉图结构。我们描述了如何将词组结构解析（包括痕迹）以可逆方式转换为新的表示形式。我们的动态程序独特地分解结构，是完整的，涵盖97.3％的宾州英语树库。我们还实现了一个概念证明分析器，它恢复了一系列空元素和跟踪类型。

##### URL
[https://arxiv.org/abs/1707.04221](https://arxiv.org/abs/1707.04221)

##### PDF
[https://arxiv.org/pdf/1707.04221](https://arxiv.org/pdf/1707.04221)

