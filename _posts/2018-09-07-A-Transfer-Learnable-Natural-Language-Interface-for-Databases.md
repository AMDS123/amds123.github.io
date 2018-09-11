---
layout: post
title: "A Transfer-Learnable Natural Language Interface for Databases"
date: 2018-09-07 19:38:51
categories: arXiv_AI
tags: arXiv_AI Knowledge Face Relation
author: Wenlu Wang, Yingtao Tian, Hongyu Xiong, Haixun Wang, Wei-Shinn Ku
mathjax: true
---

* content
{:toc}

##### Abstract
Relational database management systems (RDBMSs) are powerful because they are able to optimize and answer queries against any relational database. A natural language interface (NLI) for a database, on the other hand, is tailored to support that specific database. In this work, we introduce a general purpose transfer-learnable NLI with the goal of learning one model that can be used as NLI for any relational database. We adopt the data management principle of separating data and its schema, but with the additional support for the idiosyncrasy and complexity of natural languages. Specifically, we introduce an automatic annotation mechanism that separates the schema and the data, where the schema also covers knowledge about natural language. Furthermore, we propose a customized sequence model that translates annotated natural language queries to SQL statements. We show in experiments that our approach outperforms previous NLI methods on the WikiSQL dataset and the model we learned can be applied to another benchmark dataset OVERNIGHT without retraining.

##### Abstract (translated by Google)
关系数据库管理系统（RDBMS）功能强大，因为它们能够针对任何关系数据库优化和回答查询。另一方面，数据库的自然语言接口（NLI）被定制为支持该特定数据库。在这项工作中，我们引入了一个通用的可转移可学习的NLI，目的是学习一个可以用作任何关系数据库的NLI的模型。我们采用分离数据及其模式的数据管理原则，但是对自然语言的特性和复杂性的额外支持。具体来说，我们引入了一种自动注释机制，用于分离模式和数据，其中模式还包括有关自然语言的知识。此外，我们提出了一个定制的序列模型，它将带注释的自然语言查询转换为SQL语句。我们在实验中表明，我们的方法在WikiSQL数据集上优于以前的NLI方法，我们学到的模型可以应用于另一个基准数据集OVERNIGHT而无需重新训练。

##### URL
[http://arxiv.org/abs/1809.02649](http://arxiv.org/abs/1809.02649)

##### PDF
[http://arxiv.org/pdf/1809.02649](http://arxiv.org/pdf/1809.02649)

