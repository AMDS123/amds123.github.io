---
layout: post
title: "Geometry of Polysemy"
date: 2016-10-24 19:35:29
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Jiaqi Mu, Suma Bhat, Pramod Viswanath
mathjax: true
---

* content
{:toc}

##### Abstract
Vector representations of words have heralded a transformational approach to classical problems in NLP; the most popular example is word2vec. However, a single vector does not suffice to model the polysemous nature of many (frequent) words, i.e., words with multiple meanings. In this paper, we propose a three-fold approach for unsupervised polysemy modeling: (a) context representations, (b) sense induction and disambiguation and (c) lexeme (as a word and sense pair) representations. A key feature of our work is the finding that a sentence containing a target word is well represented by a low rank subspace, instead of a point in a vector space. We then show that the subspaces associated with a particular sense of the target word tend to intersect over a line (one-dimensional subspace), which we use to disambiguate senses using a clustering algorithm that harnesses the Grassmannian geometry of the representations. The disambiguation algorithm, which we call $K$-Grassmeans, leads to a procedure to label the different senses of the target word in the corpus -- yielding lexeme vector representations, all in an unsupervised manner starting from a large (Wikipedia) corpus in English. Apart from several prototypical target (word,sense) examples and a host of empirical studies to intuit and justify the various geometric representations, we validate our algorithms on standard sense induction and disambiguation datasets and present new state-of-the-art results.

##### Abstract (translated by Google)
词的向量表征预示了NLP中经典问题的转换方法;最流行的例子是word2vec。然而，单一的矢量不足以模拟许多（频繁的）单词的多义性质，即具有多重意义的单词。在本文中，我们提出了一种无监督多义词建模的三重方法：（a）上下文表示，（b）感觉归纳和消歧以及（c）词位（作为一个单词和意义对）表示。我们工作的一个关键特征是发现包含目标词的句子可以用低秩子空间来表示，而不是在向量空间中的一个点。然后，我们表明与目标词的特定意义相关的子空间倾向于在一条线（一维子空间）上相交，我们用它来使用利用表示的格拉斯曼几何的聚类算法来消除歧义。消歧算法（我们称之为$ K $ -Grassmeans）导致了一个过程，在语料库中标记目标词的不同感官 - 产生词位向量表示，所有这些都以无监督的方式从一个大的维基百科语料库开始英语。除了几个典型的目标（单词，意义）例子和大量的实证研究来直观和证明各种几何表示，我们验证了我们的算法在标准意义上的归纳和消歧数据集，并提出了新的最新的结果。

##### URL
[https://arxiv.org/abs/1610.07569](https://arxiv.org/abs/1610.07569)

##### PDF
[https://arxiv.org/pdf/1610.07569](https://arxiv.org/pdf/1610.07569)

