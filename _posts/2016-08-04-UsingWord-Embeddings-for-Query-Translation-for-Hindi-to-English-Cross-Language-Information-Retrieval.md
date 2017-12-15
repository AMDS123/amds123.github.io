---
layout: post
title: "UsingWord Embeddings for Query Translation for Hindi to English Cross Language Information Retrieval"
date: 2016-08-04 14:44:52
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Paheli Bhattacharya, Pawan Goyal, Sudeshna Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-Language Information Retrieval (CLIR) has become an important problem to solve in the recent years due to the growth of content in multiple languages in the Web. One of the standard methods is to use query translation from source to target language. In this paper, we propose an approach based on word embeddings, a method that captures contextual clues for a particular word in the source language and gives those words as translations that occur in a similar context in the target language. Once we obtain the word embeddings of the source and target language pairs, we learn a projection from source to target word embeddings, making use of a dictionary with word translation pairs.We then propose various methods of query translation and aggregation. The advantage of this approach is that it does not require the corpora to be aligned (which is difficult to obtain for resource-scarce languages), a dictionary with word translation pairs is enough to train the word vectors for translation. We experiment with Forum for Information Retrieval and Evaluation (FIRE) 2008 and 2012 datasets for Hindi to English CLIR. The proposed word embedding based approach outperforms the basic dictionary based approach by 70% and when the word embeddings are combined with the dictionary, the hybrid approach beats the baseline dictionary based method by 77%. It outperforms the English monolingual baseline by 15%, when combined with the translations obtained from Google Translate and Dictionary.

##### Abstract (translated by Google)
跨语言信息检索（CLIR）已经成为近年来由于网络中多语言内容的增长而需要解决的一个重要问题。其中一种标准的方法是使用从源语言到目标语言的查询翻译。在本文中，我们提出了一种基于词嵌入的方法，这种方法可以捕获源语言中特定词的上下文线索，并将这些词作为目标语言中类似上下文中出现的翻译。一旦我们获得源语言和目标语言对的嵌入词，就可以学习从源到目标词嵌入的投影，并利用带有单词翻译对的词典。然后提出了各种查询翻译和聚合的方法。这种方法的优点是它不需要对齐语料库（资源稀缺的语言很难获得），带有单词翻译对的词典足以训练单词向量进行翻译。我们试验了信息检索和评估论坛（FIRE）2008和2012的印地语到英语CLIR数据集。所提出的基于字的嵌入方法优于基于字典的基本方法70％，当字嵌入与字典相结合时，混合方法比基线字典方法节省77％。与谷歌翻译和词典的翻译相结合，它的英语单语基准性能优于15％。

##### URL
[https://arxiv.org/abs/1608.01561](https://arxiv.org/abs/1608.01561)

##### PDF
[https://arxiv.org/pdf/1608.01561](https://arxiv.org/pdf/1608.01561)

