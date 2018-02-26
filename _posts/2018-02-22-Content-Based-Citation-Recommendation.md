---
layout: post
title: "Content-Based Citation Recommendation"
date: 2018-02-22 21:13:47
categories: arXiv_CL
tags: arXiv_CL Review Recommendation
author: Chandra Bhagavatula, Sergey Feldman, Russell Power, Waleed Ammar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a content-based method for recommending citations in an academic paper draft. We embed a given query document into a vector space, then use its nearest neighbors as candidates, and rerank the candidates using a discriminative model trained to distinguish between observed and unobserved citations. Unlike previous work, our method does not require metadata such as author names which can be missing, e.g., during the peer review process. Without using metadata, our method outperforms the best reported results on PubMed and DBLP datasets with relative improvements of over 18% in F1@20 and over 22% in MRR. We show empirically that, although adding metadata improves the performance on standard metrics, it favors self-citations which are less useful in a citation recommendation setup. We release an online portal (this http URL) for citation recommendation based on our method, and a new dataset OpenCorpus of 7 million research articles to facilitate future research on this task.

##### Abstract (translated by Google)
我们提出了一种基于内容的方法来推荐学术论文草案中的引文。我们将给定的查询文档嵌入到向量空间中，然后使用其最近的邻居作为候选者，并使用区分观察和未观察引文的区分模型重新排列候选人。与以前的工作不同，我们的方法不需要可能缺失的元数据，例如作者姓名，例如在同行评审过程中。在不使用元数据的情况下，我们的方法优于PubMed和DBLP数据集的最佳报告结果，相对于MR @ 20的相对改进超过18％，MRR超过22％。我们凭经验显示，尽管添加元数据可以提高标准度量的性能，但它有利于自引，这在引文推荐设置中不太有用。我们根据我们的方法发布了一个用于引文推荐的在线门户网站（此http URL），以及一份700万篇研究文章的新数据集OpenCorpus，以便于今后对此任务进行研究。

##### URL
[https://arxiv.org/abs/1802.08301](https://arxiv.org/abs/1802.08301)

##### PDF
[https://arxiv.org/pdf/1802.08301](https://arxiv.org/pdf/1802.08301)

