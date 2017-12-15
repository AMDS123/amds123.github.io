---
layout: post
title: "Unsupervised Learning for Lexicon-Based Classification"
date: 2016-11-21 18:30:17
categories: arXiv_CL
tags: arXiv_CL Sentiment Classification
author: Jacob Eisenstein
mathjax: true
---

* content
{:toc}

##### Abstract
In lexicon-based classification, documents are assigned labels by comparing the number of words that appear from two opposed lexicons, such as positive and negative sentiment. Creating such words lists is often easier than labeling instances, and they can be debugged by non-experts if classification performance is unsatisfactory. However, there is little analysis or justification of this classification heuristic. This paper describes a set of assumptions that can be used to derive a probabilistic justification for lexicon-based classification, as well as an analysis of its expected accuracy. One key assumption behind lexicon-based classification is that all words in each lexicon are equally predictive. This is rarely true in practice, which is why lexicon-based approaches are usually outperformed by supervised classifiers that learn distinct weights on each word from labeled instances. This paper shows that it is possible to learn such weights without labeled data, by leveraging co-occurrence statistics across the lexicons. This offers the best of both worlds: light supervision in the form of lexicons, and data-driven classification with higher accuracy than traditional word-counting heuristics.

##### Abstract (translated by Google)
在基于词汇的分类中，文档通过比较两个相反词典中出现的单词数量（例如正面和负面情绪）来分配标签。创建这样的单词列表通常比标记实例更容易，如果分类性能不理想，可以由非专家进行调试。然而，这种分类启发式分析或者说理由很少。本文描述了一组假设，可用于推导基于词典的分类的概率论证，并分析其预期的准确性。基于词典分类的一个关键假设是每个词汇中的所有单词都具有相同的预测性。这在实践中很少是真实的，这就是为什么基于词典的方法通常优于监督分类器，其从标记的实例中学习每个词的不同权重。本文表明，通过利用词典中的同现统计，可以学习没有标记数据的权重。这提供了两全其美的方法：以词典形式的轻量级监督，以及比传统的字数统计启发式算法更准确的数据驱动分类。

##### URL
[https://arxiv.org/abs/1611.06933](https://arxiv.org/abs/1611.06933)

##### PDF
[https://arxiv.org/pdf/1611.06933](https://arxiv.org/pdf/1611.06933)

