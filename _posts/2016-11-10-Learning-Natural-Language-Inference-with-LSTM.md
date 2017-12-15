---
layout: post
title: "Learning Natural Language Inference with LSTM"
date: 2016-11-10 11:54:29
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Inference RNN Classification Relation
author: Shuohang Wang, Jing Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language inference (NLI) is a fundamentally important task in natural language processing that has many applications. The recently released Stanford Natural Language Inference (SNLI) corpus has made it possible to develop and evaluate learning-centered methods such as deep neural networks for natural language inference (NLI). In this paper, we propose a special long short-term memory (LSTM) architecture for NLI. Our model builds on top of a recently proposed neural attention model for NLI but is based on a significantly different idea. Instead of deriving sentence embeddings for the premise and the hypothesis to be used for classification, our solution uses a match-LSTM to perform word-by-word matching of the hypothesis with the premise. This LSTM is able to place more emphasis on important word-level matching results. In particular, we observe that this LSTM remembers important mismatches that are critical for predicting the contradiction or the neutral relationship label. On the SNLI corpus, our model achieves an accuracy of 86.1%, outperforming the state of the art.

##### Abstract (translated by Google)
自然语言推理（NLI）是自然语言处理中一个非常重要的任务，有很多应用。最近发布的斯坦福自然语言推理（SNLI）语料库使得开发和评估以学习为中心的方法成为可能，例如用于自然语言推理（NLI）的深度神经网络。在本文中，我们针对NLI提出了一种特殊的长时间短时记忆（LSTM）体系结构。我们的模型建立在最近提出的用于NLI的神经注意模型之上，但基于一个明显不同的想法。我们的解决方案使用匹配LSTM来替代为前提导出句子嵌入和用于分类的假设，而是使用匹配LSTM来执行假设与前提的逐字匹配。这个LSTM能够把重点放在重要的字级匹配结果上。特别是，我们观察到，这个LSTM记住了对于预测矛盾或中性关系标签至关重要的重要的不匹配。在SNLI语料库上，我们的模型达到了86.1％的准确度，超越了现有技术水平。

##### URL
[https://arxiv.org/abs/1512.08849](https://arxiv.org/abs/1512.08849)

##### PDF
[https://arxiv.org/pdf/1512.08849](https://arxiv.org/pdf/1512.08849)

