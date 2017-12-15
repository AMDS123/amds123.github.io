---
layout: post
title: "Entity Identification as Multitasking"
date: 2017-07-21 16:03:13
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Prediction Detection
author: Karl Stratos
mathjax: true
---

* content
{:toc}

##### Abstract
Standard approaches in entity identification hard-code boundary detection and type prediction into labels (e.g., John/B-PER Smith/I-PER) and then perform Viterbi. This has two disadvantages: 1. the runtime complexity grows quadratically in the number of types, and 2. there is no natural segment-level representation. In this paper, we propose a novel neural architecture that addresses these disadvantages. We frame the problem as multitasking, separating boundary detection and type prediction but optimizing them jointly. Despite its simplicity, this architecture performs competitively with fully structured models such as BiLSTM-CRFs while scaling linearly in the number of types. Furthermore, by construction, the model induces type-disambiguating embeddings of predicted mentions.

##### Abstract (translated by Google)
在实体识别硬码边界检测和标签类型预测（例如，John / B-PER Smith / I-PER）中的标准方法，然后执行维特比。这有两个缺点：1.运行时复杂度在类型数量上呈二次曲线增长，2.没有自然的段级表示。在本文中，我们提出了一种新的神经架构来解决这些缺点。我们将问题定义为多任务处理，分离边界检测和类型预测，但是共同优化它们。尽管它的简单性，这种架构与诸如BiLSTM-CRF之类的完全结构化的模型竞争性地进行竞争，同时在类型数量上线性地进行缩放。此外，通过构建，该模型引入了预测提及的类型歧义嵌入。

##### URL
[https://arxiv.org/abs/1612.02706](https://arxiv.org/abs/1612.02706)

##### PDF
[https://arxiv.org/pdf/1612.02706](https://arxiv.org/pdf/1612.02706)

