---
layout: post
title: "Solving Verbal Comprehension Questions in IQ Test by Knowledge-Powered Word Embedding"
date: 2016-04-26 11:37:32
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Classification Deep_Learning Relation
author: Huazheng Wang, Fei Tian, Bin Gao, Jiang Bian, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Intelligence Quotient (IQ) Test is a set of standardized questions designed to evaluate human intelligence. Verbal comprehension questions appear very frequently in IQ tests, which measure human's verbal ability including the understanding of the words with multiple senses, the synonyms and antonyms, and the analogies among words. In this work, we explore whether such tests can be solved automatically by artificial intelligence technologies, especially the deep learning technologies that are recently developed and successfully applied in a number of fields. However, we found that the task was quite challenging, and simply applying existing technologies (e.g., word embedding) could not achieve a good performance, mainly due to the multiple senses of words and the complex relations among words. To tackle these challenges, we propose a novel framework consisting of three components. First, we build a classifier to recognize the specific type of a verbal question (e.g., analogy, classification, synonym, or antonym). Second, we obtain distributed representations of words and relations by leveraging a novel word embedding method that considers the multi-sense nature of words and the relational knowledge among words (or their senses) contained in dictionaries. Third, for each type of questions, we propose a specific solver based on the obtained distributed word representations and relation representations. Experimental results have shown that the proposed framework can not only outperform existing methods for solving verbal comprehension questions but also exceed the average performance of the Amazon Mechanical Turk workers involved in the study. The results indicate that with appropriate uses of the deep learning technologies we might be a further step closer to the human intelligence.

##### Abstract (translated by Google)
智商（IQ）测试是一组旨在评估人类智力的标准化问题。言语理解问题在IQ测试中出现得非常频繁，它测量人类的语言能力，包括理解多义词，同义词和反义词，以及词之间的类比。在这项工作中，我们探讨这种测试是否可以通过人工智能技术自动解决，特别是最近在多个领域开发和成功应用的深度学习技术。然而，我们发现这个任务是相当有挑战性的，单纯应用现有技术（如文字嵌入）就无法取得好的效果，主要是由于词汇的多重感知和词汇之间的复杂关系。为了解决这些挑战，我们提出了一个由三个部分组成的新颖框架。首先，我们建立一个分类器来识别口头问题的具体类型（例如类比，分类，同义词或反义词）。其次，通过利用考虑词的多义性和词典中包含的词（或其意义）之间的关系知识的新颖词嵌入方法，获得词和关系的分布式表示。第三，针对每种类型的问题，我们基于获得的分布式词表示和关系表示，提出了一个具体的求解器。实验结果表明，所提出的框架不仅可以超越解决口头理解问题的现有方法，而且超过了参与研究的亚马逊机械特克员工的平均表现。结果表明，通过适当使用深度学习技术，我们可能会向人类智能迈进一步。

##### URL
[https://arxiv.org/abs/1505.07909](https://arxiv.org/abs/1505.07909)

##### PDF
[https://arxiv.org/pdf/1505.07909](https://arxiv.org/pdf/1505.07909)

