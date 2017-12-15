---
layout: post
title: "Multilingual Multiword Expressions"
date: 2016-12-01 14:01:00
categories: arXiv_CL
tags: arXiv_CL Relation
author: Lahari Poddar
mathjax: true
---

* content
{:toc}

##### Abstract
The project aims to provide a semi-supervised approach to identify Multiword Expressions in a multilingual context consisting of English and most of the major Indian languages. Multiword expressions are a group of words which refers to some conventional or regional way of saying things. If they are literally translated from one language to another the expression will lose its inherent meaning. To automatically extract multiword expressions from a corpus, an extraction pipeline have been constructed which consist of a combination of rule based and statistical approaches. There are several types of multiword expressions which differ from each other widely by construction. We employ different methods to detect different types of multiword expressions. Given a POS tagged corpus in English or any Indian language the system initially applies some regular expression filters to narrow down the search space to certain patterns (like, reduplication, partial reduplication, compound nouns, compound verbs, conjunct verbs etc.). The word sequences matching the required pattern are subjected to a series of linguistic tests which include verb filtering, named entity filtering and hyphenation filtering test to exclude false positives. The candidates are then checked for semantic relationships among themselves (using Wordnet). In order to detect partial reduplication we make use of Wordnet as a lexical database as well as a tool for lemmatising. We detect complex predicates by investigating the features of the constituent words. Statistical methods are applied to detect collocations. Finally, lexicographers examine the list of automatically extracted candidates to validate whether they are true multiword expressions or not and add them to the multiword dictionary accordingly.

##### Abstract (translated by Google)
该项目旨在提供一种半监督方法，在由英语和大部分主要印度语言组成的多语言环境中识别多词表达式。多词表达式是一组词，指的是一些常规或区域的说话方式。如果从一种语言到另一种语言的字面翻译，表达将失去其固有的意义。为了从语料库中自动提取多词表达式，已经构建了由基于规则和统计方法组成的提取流水线。有多种类型的多字表达式，它们彼此之间的结构差别很大。我们使用不同的方法来检测不同类型的多字表达式。给定带有英文或印度语言的POS标记的语料库，系统最初应用一些正则表达式过滤器来将搜索空间缩小到某些模式（例如，重叠，部分重叠，复合名词，复合动词，合并动词等）。匹配所需模式的单词序列经过一系列语义测试，包括动词过滤，名为实体过滤和连字符过滤测试，以排除误报。然后检查候选人之间的语义关系（使用Wordnet）。为了检测部分重叠，我们使用Wordnet作为词汇数据库以及用于lemmatising的工具。我们通过调查构成词的特征来检测复杂的谓词。统计方法被用来检测搭配。最后，词典编纂者检查自动提取的候选词列表，以验证它们是否是真正的多词表达式，并相应地将它们添加到多字词典中。

##### URL
[https://arxiv.org/abs/1612.00246](https://arxiv.org/abs/1612.00246)

##### PDF
[https://arxiv.org/pdf/1612.00246](https://arxiv.org/pdf/1612.00246)

