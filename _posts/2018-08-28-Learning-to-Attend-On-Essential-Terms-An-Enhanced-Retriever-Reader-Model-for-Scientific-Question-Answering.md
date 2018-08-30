---
layout: post
title: "Learning to Attend On Essential Terms: An Enhanced Retriever-Reader Model for Scientific Question Answering"
date: 2018-08-28 18:48:30
categories: arXiv_CL
tags: arXiv_CL QA
author: Jianmo Ni, Chenguang Zhu, Weizhu Chen, Julian McAuley
mathjax: true
---

* content
{:toc}

##### Abstract
Scientific Question Answering (SQA) is a challenging open-domain task which requires the capability to understand questions and choices, collect useful information, and reason over evidence. Previous work typically formulates this task as a reading comprehension or entailment problem given evidence retrieved from search engines. However, existing techniques struggle to retrieve indirectly related evidence when no directly related evidence is provided, especially for complex questions where it is hard to parse precisely what the question asks. In this paper we propose a retriever-reader model that learns to attend on essential terms during the question answering process. We build 1) an essential-term-aware `retriever' which first identifies the most important words in a question, then reformulates the queries and searches for related evidence 2) an enhanced `reader' to distinguish between essential terms and distracting words to predict the answer. We experimentally evaluate our model on the ARC dataset where it outperforms the existing state-of-the-art model by 8.1%.

##### Abstract (translated by Google)
科学问答（SQA）是一项具有挑战性的开放领域任务，需要具备理解问题和选择，收集有用信息和推理证据的能力。以前的工作通常会根据从搜索引擎中检索到的证据，将此任务表述为阅读理解或蕴涵问题。然而，当没有提供直接相关证据时，现有技术难以检索间接相关证据，特别是对于难以准确解析问题所要求的复杂问题。在本文中，我们提出了一个检索器 - 阅读器模型，该模型学习在问答过程中参加基本术语。我们构建1）一个基本术语感知的“猎犬”，它首先识别问题中最重要的单词，然后重新构造查询并搜索相关证据2）增强的“读者”以区分基本术语和分散注意力的单词以进行预测答案。我们在ARC数据集上通过实验评估我们的模型，它在8.1％的范围内优于现有的最先进模型。

##### URL
[http://arxiv.org/abs/1808.09492](http://arxiv.org/abs/1808.09492)

##### PDF
[http://arxiv.org/pdf/1808.09492](http://arxiv.org/pdf/1808.09492)

