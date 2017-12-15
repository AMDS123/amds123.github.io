---
layout: post
title: "Learning to Create and Reuse Words in Open-Vocabulary Neural Language Modeling"
date: 2017-04-23 21:31:22
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Kazuya Kawakami, Chris Dyer, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
Fixed-vocabulary language models fail to account for one of the most characteristic statistical facts of natural language: the frequent creation and reuse of new word types. Although character-level language models offer a partial solution in that they can create word types not attested in the training corpus, they do not capture the "bursty" distribution of such words. In this paper, we augment a hierarchical LSTM language model that generates sequences of word tokens character by character with a caching mechanism that learns to reuse previously generated words. To validate our model we construct a new open-vocabulary language modeling corpus (the Multilingual Wikipedia Corpus, MWC) from comparable Wikipedia articles in 7 typologically diverse languages and demonstrate the effectiveness of our model across this range of languages.

##### Abstract (translated by Google)
固定词汇语言模型未能说明自然语言最具特色的统计事实之一：频繁创建和重用新词类型。虽然字符级语言模型提供了一个部分的解决方案，因为他们可以创建训练语料库中没有证明的单词类型，但是他们没有捕获这种单词的“突发”分布。在本文中，我们增加了一个层次的LSTM语言模型，它可以逐个字符地生成字符序列，使用一个缓存机制学习重用以前生成的单词。为了验证我们的模型，我们使用7种类型不同的语言构建了一个新的开放式词汇语言建模语料库（多语言维基百科语料库，MWC），并展示了我们模型在这一系列语言中的有效性。

##### URL
[https://arxiv.org/abs/1704.06986](https://arxiv.org/abs/1704.06986)

##### PDF
[https://arxiv.org/pdf/1704.06986](https://arxiv.org/pdf/1704.06986)

