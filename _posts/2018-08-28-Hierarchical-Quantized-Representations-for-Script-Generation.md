---
layout: post
title: "Hierarchical Quantized Representations for Script Generation"
date: 2018-08-28 20:53:56
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Language_Model
author: Noah Weber, Leena Shekhar, Niranjan Balasubramanian, Nathanael Chambers
mathjax: true
---

* content
{:toc}

##### Abstract
Scripts define knowledge about how everyday scenarios (such as going to a restaurant) are expected to unfold. One of the challenges to learning scripts is the hierarchical nature of the knowledge. For example, a suspect arrested might plead innocent or guilty, and a very different track of events is then expected to happen. To capture this type of information, we propose an autoencoder model with a latent space defined by a hierarchy of categorical variables. We utilize a recently proposed vector quantization based approach, which allows continuous embeddings to be associated with each latent variable value. This permits the decoder to softly decide what portions of the latent hierarchy to condition on by attending over the value embeddings for a given setting. Our model effectively encodes and generates scripts, outperforming a recent language modeling-based method on several standard tasks, and allowing the autoencoder model to achieve substantially lower perplexity scores compared to the previous language modeling-based method.

##### Abstract (translated by Google)
脚本定义了有关如何展开日常场景（例如去餐馆）的知识。学习脚本的挑战之一是知识的层次性。例如，被捕的嫌疑人可能会认罪无辜或有罪，预计会发生一系列不同的事件。为了捕获这种类型的信息，我们提出了一种自动编码器模型，其潜在空间由分类变量的层次结构定义。我们利用最近提出的基于矢量量化的方法，其允许连续嵌入与每个潜在变量值相关联。这允许解码器通过参与给定设置的值嵌入来轻柔地确定潜在层级的哪些部分要进行调节。我们的模型有效地编码和生成脚本，在几个标准任务上优于最近基于语言建模的方法，并且与先前基于语言建模的方法相比，允许自动编码器模型实现显着更低的困惑度分数。

##### URL
[http://arxiv.org/abs/1808.09542](http://arxiv.org/abs/1808.09542)

##### PDF
[http://arxiv.org/pdf/1808.09542](http://arxiv.org/pdf/1808.09542)

