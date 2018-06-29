---
layout: post
title: "Record Linkage to Match Customer Names: A Probabilistic Approach"
date: 2018-06-26 19:26:47
categories: arXiv_AI
tags: arXiv_AI Knowledge Relation
author: Bahare Fatemi, Seyed Mehran Kazemi, David Poole
mathjax: true
---

* content
{:toc}

##### Abstract
Consider the following problem: given a database of records indexed by names (e.g., name of companies, restaurants, businesses, or universities) and a new name, determine whether the new name is in the database, and if so, which record it refers to. This problem is an instance of record linkage problem and is a challenging problem because people do not consistently use the official name, but use abbreviations, synonyms, different order of terms, different spelling of terms, short form of terms, and the name can contain typos or spacing issues. We provide a probabilistic model using relational logistic regression to find the probability of each record in the database being the desired record for a given query and find the best record(s) with respect to the probabilities. Building on term-matching and translational approaches for search, our model addresses many of the aforementioned challenges and provides good results when existing baselines fail. Using the probabilities outputted by the model, we can automate the search process for a portion of queries whose desired documents get a probability higher than a trust threshold. We evaluate our model on a large real-world dataset from a telecommunications company and compare it to several state-of-the-art baselines. The obtained results show that our model is a promising probabilistic model for record linkage for names. We also test if the knowledge learned by our model on one domain can be effectively transferred to a new domain. For this purpose, we test our model on an unseen test set from the business names of the secondString dataset. Promising results show that our model can be effectively applied to unseen datasets. Finally, we study the sensitivity of our model to the statistics of datasets.

##### Abstract (translated by Google)
考虑以下问题：给定由名称索引的记录（例如，公司，餐馆，企业或大学的名称）和新名称的数据库，确定新名称是否在数据库中，如果是的话，它指向哪个记录至。这个问题是记录链接问题的一个实例，并且是一个具有挑战性的问题，因为人们并不一致地使用官方名称，而是使用缩写，同义词，不同的术语顺序，术语的不同拼写，术语的简短形式以及名称可以包含错字或空格问题。我们提供了一个使用关系逻辑回归的概率模型来查找数据库中每个记录的概率，作为给定查询的期望记录，并找出关于概率的最佳记录。基于术语匹配和翻译方法进行搜索，我们的模型解决了上述许多挑战，并在现有基线失败时提供良好结果。使用模型输出的概率，我们可以对一部分查询自动执行搜索过程，其中所需文档的概率高于信任阈值。我们在来自电信公司的大型现实世界数据集上评估我们的模型，并将其与几个最先进的基线进行比较。得到的结果表明，我们的模型是一个很有前途的名字记录链接概率模型。我们还测试我们的模型在一个领域学到的知识是否可以有效地转移到一个新的领域。为此，我们在来自secondString数据集的业务名称的不可见的测试集上测试我们的模型。有希望的结果表明，我们的模型可以有效地应用于不可见的数据集。最后，我们研究模型对数据集统计的敏感性。

##### URL
[http://arxiv.org/abs/1806.10928](http://arxiv.org/abs/1806.10928)

##### PDF
[http://arxiv.org/pdf/1806.10928](http://arxiv.org/pdf/1806.10928)

