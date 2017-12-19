---
layout: post
title: "Language Segmentation"
date: 2015-10-06 19:35:23
categories: arXiv_CL
tags: arXiv_CL Segmentation Weakly_Supervised Language_Model
author: David Alfter
mathjax: true
---

* content
{:toc}

##### Abstract
Language segmentation consists in finding the boundaries where one language ends and another language begins in a text written in more than one language. This is important for all natural language processing tasks. The problem can be solved by training language models on language data. However, in the case of low- or no-resource languages, this is problematic. I therefore investigate whether unsupervised methods perform better than supervised methods when it is difficult or impossible to train supervised approaches. A special focus is given to difficult texts, i.e. texts that are rather short (one sentence), containing abbreviations, low-resource languages and non-standard language. I compare three approaches: supervised n-gram language models, unsupervised clustering and weakly supervised n-gram language model induction. I devised the weakly supervised approach in order to deal with difficult text specifically. In order to test the approach, I compiled a small corpus of different text types, ranging from one-sentence texts to texts of about 300 words. The weakly supervised language model induction approach works well on short and difficult texts, outperforming the clustering algorithm and reaching scores in the vicinity of the supervised approach. The results look promising, but there is room for improvement and a more thorough investigation should be undertaken.

##### Abstract (translated by Google)
语言分段包括找到一种语言结束的边界，另一种语言在用多种语言写成的文本中开始。这对所有自然语言处理任务都很重要。这个问题可以通过训练语言数据的语言模型来解决。但是，在低资源或无资源语言的情况下，这是有问题的。因此，我们调查无监督方法是否难以或不可能训练监督方法，而不是监督方法。特别关注困难的文本，即包含缩写，低资源语言和非标准语言的相当短的文本（一个句子）。我比较了三种方法：监督n元语言模型，无监督聚类和弱监督n元语言模型归纳。我设计了弱监督的方式，专门处理难题。为了测试方法，我编写了一个不同文本类型的小语料库，从一个句子的文本到约300个单词的文本。弱监督语言模型归纳方法在短文本和难文本文本上效果良好，优于聚类算法，并在监督方法附近得分。结果看起来很有希望，但还有改进的空间，应该进行更彻底的调查。

##### URL
[https://arxiv.org/abs/1510.01717](https://arxiv.org/abs/1510.01717)

##### PDF
[https://arxiv.org/pdf/1510.01717](https://arxiv.org/pdf/1510.01717)

