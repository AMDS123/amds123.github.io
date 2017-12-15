---
layout: post
title: "End-to-End Answer Chunk Extraction and Ranking for Reading Comprehension"
date: 2016-11-02 17:55:32
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Yang Yu, Wei Zhang, Kazi Hasan, Mo Yu, Bing Xiang, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes dynamic chunk reader (DCR), an end-to-end neural reading comprehension (RC) model that is able to extract and rank a set of answer candidates from a given document to answer questions. DCR is able to predict answers of variable lengths, whereas previous neural RC models primarily focused on predicting single tokens or entities. DCR encodes a document and an input question with recurrent neural networks, and then applies a word-by-word attention mechanism to acquire question-aware representations for the document, followed by the generation of chunk representations and a ranking module to propose the top-ranked chunk as the answer. Experimental results show that DCR achieves state-of-the-art exact match and F1 scores on the SQuAD dataset.

##### Abstract (translated by Google)
本文提出了动态块读取器（DCR），一种端到端的神经阅读理解（RC）模型，能够从给定的文档中提取和排列一组答案候选者来回答问题。 DCR能够预测可变长度的答案，而以前的神经RC模型主要集中于预测单个标记或实体。 DCR使用递归神经网络对文档和输入问题进行编码，然后应用逐词注意机制来获取文档的问题意识表示，随后生成块表示和排序模块，排名大块为答案。实验结果表明，DCR在SQUAD数据集上达到了最新的精确匹配和F1得分。

##### URL
[https://arxiv.org/abs/1610.09996](https://arxiv.org/abs/1610.09996)

##### PDF
[https://arxiv.org/pdf/1610.09996](https://arxiv.org/pdf/1610.09996)

