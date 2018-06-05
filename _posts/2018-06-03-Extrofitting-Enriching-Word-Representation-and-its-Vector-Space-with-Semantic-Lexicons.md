---
layout: post
title: "Extrofitting: Enriching Word Representation and its Vector Space with Semantic Lexicons"
date: 2018-06-03 08:35:28
categories: arXiv_AI
tags: arXiv_AI Knowledge Language_Model
author: Hwiyeol Jo, Stanley Jungkyu Choi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose post-processing method for enriching not only word representation but also its vector space using semantic lexicons, which we call extrofitting. The method consists of 3 steps as follows: (i) Expanding 1 or more dimension(s) on all the word vectors, filling with their representative value. (ii) Transferring semantic knowledge by averaging each representative values of synonyms and filling them in the expanded dimension(s). These two steps make representations of the synonyms close together. (iii) Projecting the vector space using Linear Discriminant Analysis, which eliminates the expanded dimension(s) with semantic knowledge. When experimenting with GloVe, we find that our method outperforms Faruqui's retrofitting on some of word similarity task. We also report further analysis on our method in respect to word vector dimensions, vocabulary size as well as other well-known pretrained word vectors (e.g., Word2Vec, Fasttext).

##### Abstract (translated by Google)
我们提出的后处理方法不仅可以丰富词表示，而且还可以使用语义词典丰富其向量空间，我们称之为扩展。该方法由以下3个步骤组成：（i）在所有单词向量上展开1个或多个维度，填充其代表值。 （ii）通过对同义词的每个代表性值进行平均并将其填充到展开的维度中来传递语义知识。这两个步骤使得同义词的表示更接近。 （iii）使用线性判别分析来投影矢量空间，其通过语义知识消除扩展的维度。在使用GloVe进行实验时，我们发现我们的方法优于Faruqui对某些词语相似性任务的改进。我们还报告了关于我们的方法在词向量维度，词汇量以及其他众所周知的预训练词向量（例如Word2Vec，Fasttext）方面的进一步分析。

##### URL
[http://arxiv.org/abs/1804.07946](http://arxiv.org/abs/1804.07946)

##### PDF
[http://arxiv.org/pdf/1804.07946](http://arxiv.org/pdf/1804.07946)

