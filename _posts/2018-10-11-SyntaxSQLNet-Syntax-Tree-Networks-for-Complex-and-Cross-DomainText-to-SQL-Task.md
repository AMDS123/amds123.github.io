---
layout: post
title: "SyntaxSQLNet: Syntax Tree Networks for Complex and Cross-DomainText-to-SQL Task"
date: 2018-10-11 20:24:13
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention
author: Tao Yu, Michihiro Yasunaga, Kai Yang, Rui Zhang, Dongxu Wang, Zifan Li, Dragomir Radev
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing studies in text-to-SQL tasks do not require generating complex SQL queries with multiple clauses or sub-queries, and generalizing to new, unseen databases. In this paper we propose SyntaxSQLNet, a syntax tree network to address the complex and cross-domain text-to-SQL generation task. SyntaxSQLNet employs a SQL specific syntax tree-based decoder with SQL generation path history and table-aware column attention encoders. We evaluate SyntaxSQLNet on the Spider text-to-SQL task, which contains databases with multiple tables and complex SQL queries with multiple SQL clauses and nested queries. We use a database split setting where databases in the test set are unseen during training. Experimental results show that SyntaxSQLNet can handle a significantly greater number of complex SQL examples than prior work, outperforming the previous state-of-the-art model by 8.3% in exact matching accuracy. We also show that SyntaxSQLNet can further improve the performance by an additional 8.1% using a cross-domain augmentation method, resulting in a 16.4% improvement in total. To our knowledge, we are the first to study this complex and cross-domain text-to-SQL task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05237](https://arxiv.org/abs/1810.05237)

##### PDF
[https://arxiv.org/pdf/1810.05237](https://arxiv.org/pdf/1810.05237)

