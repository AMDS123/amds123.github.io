---
layout: post
title: "Enforcing Constraints on Outputs with Unconstrained Inference"
date: 2017-07-26 19:00:10
categories: arXiv_CL
tags: arXiv_CL Inference
author: Jay Yoon Lee, Michael Wick, Jean-Baptiste Tristan, Jaime Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Increasingly, practitioners apply neural networks to complex problems in natural language processing (NLP), such as syntactic parsing, that have rich output structures. Many such applications require deterministic constraints on the output values; for example, requiring that the sequential outputs encode a valid tree. While hidden units might capture such properties, the network is not always able to learn them from the training data alone, and practitioners must then resort to post-processing. In this paper, we present an inference method for neural networks that enforces deterministic constraints on outputs without performing post-processing or expensive discrete search over the feasible space. Instead, for each input, we nudge the continuous weights until the network's unconstrained inference procedure generates an output that satisfies the constraints. We find that our method reduces the number of violating outputs by up to 94%, while improving accuracy in constituency parsing.

##### Abstract (translated by Google)
从业者越来越多地将神经网络应用于自然语言处理（NLP）中复杂的问题，如句法分析，具有丰富的输出结构。许多这样的应用程序需要输出值的确定性约束;例如，要求顺序输出编码一个有效的树。虽然隐藏的单位可能会捕获这些属性，但网络并不总是能够单独从训练数据中学习，而实践者则必须求助于后处理。在本文中，我们提出了一个神经网络的推理方法，强制输出的确定性约束，而无需执行后处理或昂贵的可行空间的离散搜索。相反，对于每个输入，我们推动连续权重，直到网络的无约束推理过程产生满足约束条件的输出。我们发现，我们的方法减少了高达94％的违规产出，同时提高了选区分析的准确性。

##### URL
[https://arxiv.org/abs/1707.08608](https://arxiv.org/abs/1707.08608)

##### PDF
[https://arxiv.org/pdf/1707.08608](https://arxiv.org/pdf/1707.08608)

