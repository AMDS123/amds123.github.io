---
layout: post
title: "AMUSE: Multilingual Semantic Parsing for Question Answering over Linked Data"
date: 2018-02-26 13:50:14
categories: arXiv_AI
tags: arXiv_AI QA Embedding Inference
author: Sherzod Hakimov, Soufian Jebbara, Philipp Cimiano
mathjax: true
---

* content
{:toc}

##### Abstract
The task of answering natural language questions over RDF data has received wide interest in recent years, in particular in the context of the series of QALD benchmarks. The task consists of mapping a natural language question to an executable form, e.g. SPARQL, so that answers from a given KB can be extracted. So far, most systems proposed are i) monolingual and ii) rely on a set of hard-coded rules to interpret questions and map them into a SPARQL query. We present the first multilingual QALD pipeline that induces a model from training data for mapping a natural language question into logical form as probabilistic inference. In particular, our approach learns to map universal syntactic dependency representations to a language-independent logical form based on DUDES (Dependency-based Underspecified Discourse Representation Structures) that are then mapped to a SPARQL query as a deterministic second step. Our model builds on factor graphs that rely on features extracted from the dependency graph and corresponding semantic representations. We rely on approximate inference techniques, Markov Chain Monte Carlo methods in particular, as well as Sample Rank to update parameters using a ranking objective. Our focus lies on developing methods that overcome the lexical gap and present a novel combination of machine translation and word embedding approaches for this purpose. As a proof of concept for our approach, we evaluate our approach on the QALD-6 datasets for English, German &amp; Spanish.

##### Abstract (translated by Google)
回答关于RDF数据的自然语言问题的任务近年来受到广泛的关注，特别是在QALD系列基准测试中。该任务包括将自然语言问题映射到可执行形式，例如， SPARQL，以便可以提取给定KB的答案。到目前为止，大多数提出的系统是i）单语言的，ii）依靠一组硬编码规则来解释问题并将它们映射到SPARQL查询中。我们提出了第一个多语言QALD流水线，该流水线从训练数据中导出模型，将自然语言问题映射为逻辑形式作为概率推理。特别是，我们的方法学习将通用语法依赖表示映射到基于DUDES（基于依赖关系的未指定语篇表示结构）的语言无关逻辑形式，然后映射到SPARQL查询作为确定性第二步。我们的模型建立在依赖于从依赖图提取的特征和相应的语义表示的因子图上。我们依赖于近似推理技术，特别是马尔可夫链蒙特卡罗方法，以及样本秩来使用排名目标来更新参数。我们的重点在于开发克服词汇鸿沟的方法，并为此目的提出机器翻译和词嵌入方法的新颖组合。作为我们方法的一个概念证明，我们评估了我们在QALD-6数据集上的方法，用于英语，德语和英语。西班牙。

##### URL
[http://arxiv.org/abs/1802.09296](http://arxiv.org/abs/1802.09296)

##### PDF
[http://arxiv.org/pdf/1802.09296](http://arxiv.org/pdf/1802.09296)

