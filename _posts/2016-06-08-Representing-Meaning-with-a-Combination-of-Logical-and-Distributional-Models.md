---
layout: post
title: "Representing Meaning with a Combination of Logical and Distributional Models"
date: 2016-06-08 15:07:47
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: I. Beltagy, Stephen Roller, Pengxiang Cheng, Katrin Erk, Raymond J. Mooney
mathjax: true
---

* content
{:toc}

##### Abstract
NLP tasks differ in the semantic information they require, and at this time no single se- mantic representation fulfills all requirements. Logic-based representations characterize sentence structure, but do not capture the graded aspect of meaning. Distributional models give graded similarity ratings for words and phrases, but do not capture sentence structure in the same detail as logic-based approaches. So it has been argued that the two are complementary. We adopt a hybrid approach that combines logic-based and distributional semantics through probabilistic logic inference in Markov Logic Networks (MLNs). In this paper, we focus on the three components of a practical system integrating logical and distributional models: 1) Parsing and task representation is the logic-based part where input problems are represented in probabilistic logic. This is quite different from representing them in standard first-order logic. 2) For knowledge base construction we form weighted inference rules. We integrate and compare distributional information with other sources, notably WordNet and an existing paraphrase collection. In particular, we use our system to evaluate distributional lexical entailment approaches. We use a variant of Robinson resolution to determine the necessary inference rules. More sources can easily be added by mapping them to logical rules; our system learns a resource-specific weight that corrects for scaling differences between resources. 3) In discussing probabilistic inference, we show how to solve the inference problems efficiently. To evaluate our approach, we use the task of textual entailment (RTE), which can utilize the strengths of both logic-based and distributional representations. In particular we focus on the SICK dataset, where we achieve state-of-the-art results.

##### Abstract (translated by Google)
NLP任务在他们所需要的语义信息上有所不同，目前没有单一的语义表达能满足所有的要求。基于逻辑的表征描述句子结构的特征，但不捕捉意义的分级方面。分布模型给出了单词和短语的分级相似性评级，但是没有像基于逻辑的方法那样捕捉句子结构的细节。所以有人认为这两者是相辅相成的。我们采用一种混合方法，通过马尔可夫逻辑网络（MLNs）中的概率逻辑推理将基于逻辑和分布语义相结合。在本文中，我们将重点放在一个集成逻辑和分布模型的实际系统的三个组成部分：1）解析和任务表示是在概率逻辑中表示输入问题的逻辑部分。这与在标准的一阶逻辑中表示它们是完全不同的。 2）对于知识库建设我们形成加权推理规则。我们整合和比较分布信息与其他来源，特别是WordNet和现有的释义集合。特别是，我们使用我们的系统来评估分布式词汇蕴涵方法。我们使用鲁宾逊分辨率的变体来确定必要的推理规则。可以通过将其映射到逻辑规则来轻松添加更多源代码;我们的系统学习资源特定的权重，纠正资源之间的缩放差异。 3）在讨论概率推理时，我们展示了如何有效地解决推理问题。为了评估我们的方法，我们使用文本包含（RTE）的任务，它可以利用基于逻辑和分布表示的优势。特别是我们专注于SICK数据集，我们获得了最先进的结果。

##### URL
[https://arxiv.org/abs/1505.06816](https://arxiv.org/abs/1505.06816)

##### PDF
[https://arxiv.org/pdf/1505.06816](https://arxiv.org/pdf/1505.06816)

