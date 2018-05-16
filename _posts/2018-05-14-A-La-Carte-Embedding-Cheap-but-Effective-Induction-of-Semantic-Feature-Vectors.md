---
layout: post
title: "A La Carte Embedding: Cheap but Effective Induction of Semantic Feature Vectors"
date: 2018-05-14 19:11:33
categories: arXiv_AI
tags: arXiv_AI Embedding Transfer_Learning Classification Language_Model
author: Mikhail Khodak, Nikunj Saunshi, Yingyu Liang, Tengyu Ma, Brandon Stewart, Sanjeev Arora
mathjax: true
---

* content
{:toc}

##### Abstract
Motivations like domain adaptation, transfer learning, and feature learning have fueled interest in inducing embeddings for rare or unseen words, n-grams, synsets, and other textual features. This paper introduces a la carte embedding, a simple and general alternative to the usual word2vec-based approaches for building such representations that is based upon recent theoretical results for GloVe-like embeddings. Our method relies mainly on a linear transformation that is efficiently learnable using pretrained word vectors and linear regression. This transform is applicable on the fly in the future when a new text feature or rare word is encountered, even if only a single usage example is available. We introduce a new dataset showing how the a la carte method requires fewer examples of words in context to learn high-quality embeddings and we obtain state-of-the-art results on a nonce task and some unsupervised document classification tasks.

##### Abstract (translated by Google)
诸如领域适应，转移学习和特征学习等动机激发了对罕见或不可见的单词，n-gram，synsets和其他文本特征嵌入的兴趣。本文介绍了一种单点嵌入，一种简单而通用的替代方法，用于构建基于GloVe类嵌入最近理论结果的常用基于2vec的方法来构建此类表示。我们的方法主要依赖于使用预训练词向量和线性回归进行有效学习的线性变换。即使只有一个使用示例可用，此转换在将来遇到新的文本功能或罕见字词时也可应用。我们引入了一个新的数据集，显示点菜方法如何在上下文中需要较少的单词例子来学习高质量的嵌入，并且我们在一个随机任务和一些无监督的文档分类任务上获得了最新的结果。

##### URL
[http://arxiv.org/abs/1805.05388](http://arxiv.org/abs/1805.05388)

##### PDF
[http://arxiv.org/pdf/1805.05388](http://arxiv.org/pdf/1805.05388)

