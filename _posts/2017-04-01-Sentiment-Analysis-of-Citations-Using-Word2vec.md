---
layout: post
title: "Sentiment Analysis of Citations Using Word2vec"
date: 2017-04-01 14:53:54
categories: arXiv_SD
tags: arXiv_SD Sentiment Embedding Classification Language_Model
author: Haixia Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Citation sentiment analysis is an important task in scientific paper analysis. Existing machine learning techniques for citation sentiment analysis are focusing on labor-intensive feature engineering, which requires large annotated corpus. As an automatic feature extraction tool, word2vec has been successfully applied to sentiment analysis of short texts. In this work, I conducted empirical research with the question: how well does word2vec work on the sentiment analysis of citations? The proposed method constructed sentence vectors (sent2vec) by averaging the word embeddings, which were learned from Anthology Collections (ACL-Embeddings). I also investigated polarity-specific word embeddings (PS-Embeddings) for classifying positive and negative citations. The sentence vectors formed a feature space, to which the examined citation sentence was mapped to. Those features were input into classifiers (support vector machines) for supervised classification. Using 10-cross-validation scheme, evaluation was conducted on a set of annotated citations. The results showed that word embeddings are effective on classifying positive and negative citations. However, hand-crafted features performed better for the overall classification.

##### Abstract (translated by Google)
引用情感分析是科学论文分析的一项重要任务。引用情感分析的现有机器学习技术主要集中在劳动密集型特征工程上，这需要大量的注释语料库。作为一种自动特征提取工具，word2vec已经成功应用于短文本的情感分析。在这项工作中，我进行了实证研究，这个问题是：word2vec在引用的情感分析上有多好？所提出的方法通过对来自Anthology Collections（ACL-Embeddings）的单词嵌入进行平均来构造句子向量（sent2vec）。我还研究了用于分类正面和负面引文的极性专用词嵌入（PS-Embeddings）。语句向量形成了被检查的引用语句被映射到的特征空间。这些特征被输入到用于监督分类的分类器（支持向量机）中。使用10个交叉验证方案，对一组注释引用进行评估。结果表明，词嵌入对正面和负面引文的分类是有效的。但是，手工特征在整体分类上表现更好。

##### URL
[https://arxiv.org/abs/1704.00177](https://arxiv.org/abs/1704.00177)

##### PDF
[https://arxiv.org/pdf/1704.00177](https://arxiv.org/pdf/1704.00177)

