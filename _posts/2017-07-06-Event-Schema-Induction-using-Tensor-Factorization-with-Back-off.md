---
layout: post
title: "Event Schema Induction using Tensor Factorization with Back-off"
date: 2017-07-06 18:02:12
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge
author: Madhav Nimishakavi, Partha Talukdar
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of Event Schema Induction(ESI) is to identify schemas of events from a corpus of documents. For example, given documents from the sports domain, we would like to infer that win(WinningPlayer, Trophy, OpponentPlayer, Location) is an important event schema for this domain. Automatic discovery of such event schemas is an important first step towards building domain-specific Knowledge Graphs (KGs). ESI has been the focus of some prior research, with generative models achieving the best performance. In this paper,we propose TFB, a tensor factorization-based method with back-off for ESI. TFB solves a novel objective to factorize Open Information Extraction (OpenIE) tuples for inducing binary schemas. Event schemas are induced out of this set of binary schemas by solving a constrained clique problem. To the best of our knowledge this is the first application of tensor factorization for the ESI problem. TFB outperforms current state-of-the-art by 52 (absolute) points gain in accuracy, while achieving 90x speedup on average. We hope to make all the code and datasets used in the paper publicly available upon publication of the paper.

##### Abstract (translated by Google)
事件模式归纳（Event Schema Induction，ESI）的目标是从文档语料库中识别事件的模式。例如，给定来自体育领域的文档，我们想推断胜利（WinningPlayer，Trophy，OpponentPlayer，Location）是该领域的重要事件模式。自动发现此类事件模式是构建特定领域知识图（KG）的重要的第一步。 ESI一直是一些先前研究的重点，生成模型达到最佳性能。在本文中，我们提出了TFB，一种基于张量分解的ESI退避算法。 TFB解决了一个新的目标，以分解开放信息抽取（OpenIE）元组来诱导二进制模式。事件模式是通过解决约束集团问题而从这组二进制模式中产生的。就我们所知，这是ESI问题中张量因子分解的首次应用。 TFB的性能比目前的最新技术水平提高了52（绝对）点，同时平均实现了90倍的加速。我们希望在论文发表后能够公开使用论文中使用的所有代码和数据集。

##### URL
[https://arxiv.org/abs/1707.01917](https://arxiv.org/abs/1707.01917)

##### PDF
[https://arxiv.org/pdf/1707.01917](https://arxiv.org/pdf/1707.01917)

