---
layout: post
title: "Table-to-Text: Describing Table Region with Natural Language"
date: 2018-05-29 03:39:35
categories: arXiv_AI
tags: arXiv_AI Language_Model
author: Junwei Bao, Duyu Tang, Nan Duan, Zhao Yan, Yuanhua Lv, Ming Zhou, Tiejun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a generative model to generate a natural language sentence describing a table region, e.g., a row. The model maps a row from a table to a continuous vector and then generates a natural language sentence by leveraging the semantics of a table. To deal with rare words appearing in a table, we develop a flexible copying mechanism that selectively replicates contents from the table in the output sequence. Extensive experiments demonstrate the accuracy of the model and the power of the copying mechanism. On two synthetic datasets, WIKIBIO and SIMPLEQUESTIONS, our model improves the current state-of-the-art BLEU-4 score from 34.70 to 40.26 and from 33.32 to 39.12, respectively. Furthermore, we introduce an open-domain dataset WIKITABLETEXT including 13,318 explanatory sentences for 4,962 tables. Our model achieves a BLEU-4 score of 38.23, which outperforms template based and language model based approaches.

##### Abstract (translated by Google)
在本文中，我们提出了一个生成模型来生成描述表格区域的自然语言句子，例如一行。该模型将表中的行映射到连续的向量，然后通过利用表的语义生成自然语言句子。为了处理出现在表格中的罕见词汇，我们开发了一种灵活的复制机制，可以有选择地复制输出序列中表格的内容。大量实验证明了模型的准确性和复制机制的力量。在两个合成数据集WIKIBIO和SIMPLEQUESTIONS中，我们的模型将当前最先进的BLEU-4得分分别从34.70提高到40.26和33.32提高到39.12。此外，我们引入了开放域数据集WIKITABLETEXT，其中包含4,962个表的13,318个解释性语句。我们的模型实现了38.23的BLEU-4分数，其优于基于模板和基于语言模型的方法。

##### URL
[http://arxiv.org/abs/1805.11234](http://arxiv.org/abs/1805.11234)

##### PDF
[http://arxiv.org/pdf/1805.11234](http://arxiv.org/pdf/1805.11234)

