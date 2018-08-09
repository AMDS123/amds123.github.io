---
layout: post
title: "Learning to Focus when Ranking Answers"
date: 2018-08-08 11:06:15
categories: arXiv_CL
tags: arXiv_CL QA Attention Embedding
author: Dana Sagi, Tzoof Avny, Kira Radinsky, Eugene Agichtein
mathjax: true
---

* content
{:toc}

##### Abstract
One of the main challenges in ranking is embedding the query and document pairs into a joint feature space, which can then be fed to a learning-to-rank algorithm. To achieve this representation, the conventional state of the art approaches perform extensive feature engineering that encode the similarity of the query-answer pair. Recently, deep-learning solutions have shown that it is possible to achieve comparable performance, in some settings, by learning the similarity representation directly from data. Unfortunately, previous models perform poorly on longer texts, or on texts with significant portion of irrelevant information, or which are grammatically incorrect. To overcome these limitations, we propose a novel ranking algorithm for question answering, QARAT, which uses an attention mechanism to learn on which words and phrases to focus when building the mutual representation. We demonstrate superior ranking performance on several real-world question-answer ranking datasets, and provide visualization of the attention mechanism to otter more insights into how our models of attention could benefit ranking for difficult question answering challenges.

##### Abstract (translated by Google)
排名的主要挑战之一是将查询和文档对嵌入到联合特征空间中，然后可以将其馈送到学习到排名算法。为了实现这种表示，传统的现有技术方法执行广泛的特征工程，其编码查询 - 答案对的相似性。最近，深度学习解决方案已经表明，通过直接从数据中学习相似性表示，在某些情况下可以实现相当的性能。遗憾的是，之前的模型在较长的文本或具有大量无关信息的文本上或在语法上不正确的文本上表现不佳。为了克服这些限制，我们提出了一种新的问答方法排序算法QARAT，它使用注意机制来学习在构建相互表示时要关注哪些单词和短语。我们在几个真实的问答答排名数据集上展示了卓越的排名表现，并提供了关注机制的可视化，以便更深入地了解我们的注意力模型如何有助于排名以解决难以回答的问题。

##### URL
[http://arxiv.org/abs/1808.02724](http://arxiv.org/abs/1808.02724)

##### PDF
[http://arxiv.org/pdf/1808.02724](http://arxiv.org/pdf/1808.02724)

