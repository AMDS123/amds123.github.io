---
layout: post
title: "Enriching Word Vectors with Subword Information"
date: 2017-06-19 17:41:07
categories: arXiv_CL
tags: arXiv_CL
author: Piotr Bojanowski, Edouard Grave, Armand Joulin, Tomas Mikolov
mathjax: true
---

* content
{:toc}

##### Abstract
Continuous word representations, trained on large unlabeled corpora are useful for many natural language processing tasks. Popular models that learn such representations ignore the morphology of words, by assigning a distinct vector to each word. This is a limitation, especially for languages with large vocabularies and many rare words. In this paper, we propose a new approach based on the skipgram model, where each word is represented as a bag of character $n$-grams. A vector representation is associated to each character $n$-gram; words being represented as the sum of these representations. Our method is fast, allowing to train models on large corpora quickly and allows us to compute word representations for words that did not appear in the training data. We evaluate our word representations on nine different languages, both on word similarity and analogy tasks. By comparing to recently proposed morphological word representations, we show that our vectors achieve state-of-the-art performance on these tasks.

##### Abstract (translated by Google)
在大型未标记的语料库上训练的连续词表示对于许多自然语言处理任务是有用的。学习这种表示的流行模型通过为每个单词分配一个不同的向量来忽略单词的形态。这是一个限制，特别是对于大量词汇和许多稀有词汇的语言。在本文中，我们提出了一种基于skipgram模型的新方法，其中每个单词被表示为一包字符$ n $ -grams。向量表示与每个字符$ n $ -gram相关联;单词被表示为这些表示的总和。我们的方法速度很快，可以快速训练大型语料库的模型，并允许我们计算没有出现在训练数据中的单词的单词表示。我们用九种不同的语言评估我们的词汇表征，包括词汇相似性和类比任务。通过比较最近提出的形态词表示，我们表明，我们的载体达到这些任务的最先进的性能。

##### URL
[https://arxiv.org/abs/1607.04606](https://arxiv.org/abs/1607.04606)

##### PDF
[https://arxiv.org/pdf/1607.04606](https://arxiv.org/pdf/1607.04606)

