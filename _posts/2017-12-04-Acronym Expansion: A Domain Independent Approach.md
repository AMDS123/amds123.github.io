---
layout: post
title:  Acronym Expansion: A Domain Independent Approach
date:   2017-12-05 18:20:28
categories: CL
tags: CL
author: Aditya Thakker, Suhail Barot, Sudhir Bagul
---

* content
{:toc}

##### Abstract
Acronyms are omnipresent. They usually express information that is repetitive and well known. But acronyms can also be ambiguous because there can be multiple expansions for the same acronym. In this paper, we propose a general system for acronym expansion that can work on any acronym given some context information. We present methods for retrieving all the possible expansions of an acronym from Wikipedia and AcronymsFinder.com. We propose to use these expansions to collect all possible contexts in which these acronyms are used and then score them using a paragraph embedding technique called Doc2Vec. This method collectively led to achieving an accuracy of 90.9% in selecting the correct expansion for given acronym, on a dataset we scraped from Wikipedia with 707 distinct acronyms and 14,876 disambiguations.

##### Abstract (translated by Google)
首字母缩写词无处不在。他们通常表达重复和众所周知的信息。但缩写词也可能是不明确的，因为对于同一首字母缩写词可以有多个扩展。在本文中，我们提出了一个缩写扩展的通用系统，它可以在给出某些上下文信息的任何首字母缩写上起作用。我们提出了从Wikipedia和AcronymsFinder.com检索所有可能的首字母缩写词的方法。我们建议使用这些扩展来收集使用这些缩写词的所有可能的上下文，然后使用称为Doc2Vec的段落嵌入技术对它们进行评分。这种方法共同导致在给定首字母缩略词选择正确扩展时，在我们从维基百科获取的具有707个不同首字母缩略词和14,876个消歧的数据集上达到了90.9％的准确度。

