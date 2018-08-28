---
layout: post
title: "Gradient-based Inference for Networks with Output Constraints"
date: 2018-08-26 17:14:27
categories: arXiv_CL
tags: arXiv_CL Inference Prediction
author: Jay Yoon Lee, Michael Wick, Sanket Vaibhav Mehta, Jean-Baptiste Tristan, Jaime Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Practitioners apply neural networks to increasingly complex problems in natural language processing (NLP), such as syntactic parsing that have rich output structures. Many such structured-prediction problems require deterministic constraints on the output values; for example, in sequence-to-sequence syntactic parsing, we require that the sequential outputs encode valid trees. While hidden units might capture such properties, the network is not always able to learn such constraints from the training data alone, and practitioners must then resort to post-processing. In this paper, we present an inference method for neural networks that enforces deterministic constraints on outputs without performing rule-based post-processing or expensive discrete search. Instead, in the spirit of gradient-based training, we enforce constraints with gradient-based inference: for each input at test-time, we nudge continuous weights until the network's unconstrained inference procedure generates an output that satisfies the constraints. We apply our methods to three tasks with hard constraints: sequence transduction, constituency parsing, and semantic role labeling (SRL). In each case, the algorithm not only satisfies constraints but improves accuracy, even when the underlying network is state-of-the-art.

##### Abstract (translated by Google)
从业者将神经网络应用于自然语言处理（NLP）中日益复杂的问题，例如具有丰富输出结构的语法分析。许多这样的结构化预测问题需要对输出值进行确定性约束;例如，在序列到序列语法分析中，我们要求顺序输出编码有效树。虽然隐藏单元可能捕获这些属性，但网络并不总是能够仅从训练数据中学习这些约束，然后从业者必须采用后处理。在本文中，我们提出了一种神经网络的推理方法，该方法在不执行基于规则的后处理或昂贵的离散搜索的情况下对输出实施确定性约束。相反，在基于梯度的训练的精神中，我们使用基于梯度的推理强制执行约束：对于测试时的每个输入，我们轻推连续权重，直到网络的无约束推理过程生成满足约束的输出。我们将我们的方法应用于具有硬约束的三个任务：序列转换，选区解析和语义角色标记（SRL）。在每种情况下，即使底层网络是最先进的，该算法不仅满足约束而且提高了准确性。

##### URL
[http://arxiv.org/abs/1707.08608](http://arxiv.org/abs/1707.08608)

##### PDF
[http://arxiv.org/pdf/1707.08608](http://arxiv.org/pdf/1707.08608)

