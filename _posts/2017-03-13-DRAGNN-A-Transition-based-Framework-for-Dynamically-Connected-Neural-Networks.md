---
layout: post
title: "DRAGNN: A Transition-based Framework for Dynamically Connected Neural Networks"
date: 2017-03-13 16:36:38
categories: arXiv_SD
tags: arXiv_SD Attention Summarization
author: Lingpeng Kong, Chris Alberti, Daniel Andor, Ivan Bogatyy, David Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a compact, modular framework for constructing novel recurrent neural architectures. Our basic module is a new generic unit, the Transition Based Recurrent Unit (TBRU). In addition to hidden layer activations, TBRUs have discrete state dynamics that allow network connections to be built dynamically as a function of intermediate activations. By connecting multiple TBRUs, we can extend and combine commonly used architectures such as sequence-to-sequence, attention mechanisms, and re-cursive tree-structured models. A TBRU can also serve as both an encoder for downstream tasks and as a decoder for its own task simultaneously, resulting in more accurate multi-task learning. We call our approach Dynamic Recurrent Acyclic Graphical Neural Networks, or DRAGNN. We show that DRAGNN is significantly more accurate and efficient than seq2seq with attention for syntactic dependency parsing and yields more accurate multi-task learning for extractive summarization tasks.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个紧凑的，模块化的框架来构建新颖的循环神经架构。我们的基本模块是一个新的通用单元，即基于过渡的循环单元（TBRU）。除了隐藏层激活之外，TBRU具有离散的状态动态，允许网络连接作为中间激活的函数动态地建立。通过连接多个TBRU，我们可以扩展和组合常用的体系结构，如序列到序列，注意机制和草草建模模型。 TBRU既可以作为下游任务的编码器，也可以同时作为自己任务的解码器，从而实现更准确的多任务学习。我们称之为动态递归非循环图形神经网络（DRAGNN）。我们证明DRAGNN比seq2seq更精确和有效，注意句法依赖性分析，并为抽取摘要任务产生更准确的多任务学习。

##### URL
[https://arxiv.org/abs/1703.04474](https://arxiv.org/abs/1703.04474)

##### PDF
[https://arxiv.org/pdf/1703.04474](https://arxiv.org/pdf/1703.04474)

