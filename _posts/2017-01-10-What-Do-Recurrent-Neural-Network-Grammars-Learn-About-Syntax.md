---
layout: post
title: "What Do Recurrent Neural Network Grammars Learn About Syntax?"
date: 2017-01-10 19:15:08
categories: arXiv_CL
tags: arXiv_CL Attention RNN Language_Model Prediction
author: Adhiguna Kuncoro, Miguel Ballesteros, Lingpeng Kong, Chris Dyer, Graham Neubig, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural network grammars (RNNG) are a recently proposed probabilistic generative modeling family for natural language. They show state-of-the-art language modeling and parsing performance. We investigate what information they learn, from a linguistic perspective, through various ablations to the model and the data, and by augmenting the model with an attention mechanism (GA-RNNG) to enable closer inspection. We find that explicit modeling of composition is crucial for achieving the best performance. Through the attention mechanism, we find that headedness plays a central role in phrasal representation (with the model's latent attention largely agreeing with predictions made by hand-crafted head rules, albeit with some important differences). By training grammars without nonterminal labels, we find that phrasal representations depend minimally on nonterminals, providing support for the endocentricity hypothesis.

##### Abstract (translated by Google)
递归神经网络语法（RNNG）是最近提出的用于自然语言的概率生成建模家族。他们展示了最先进的语言建模和解析性能。我们从语言学的角度，通过对模型和数据的各种消融，以及通过注意机制（GA-RNNG）扩大模型来调查他们学习的信息，以便进一步检查。我们发现构图的显式建模对于获得最佳性能至关重要。通过注意机制，我们发现头脑在短语表征中起着核心作用（模型的潜在注意力主要与手工制定的头规则的预测一致，尽管有一些重要的差异）。通过训练没有非终结标签的语法，我们发现短语表达最少依赖于非终结点，为内心中心假说提供支持。

##### URL
[https://arxiv.org/abs/1611.05774](https://arxiv.org/abs/1611.05774)

##### PDF
[https://arxiv.org/pdf/1611.05774](https://arxiv.org/pdf/1611.05774)

