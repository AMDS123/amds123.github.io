---
layout: post
title: "DuoRC: Towards Complex Language Understanding with Paraphrased Reading Comprehension"
date: 2018-05-10 05:59:37
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Amrita Saha, Rahul Aralikatte, Mitesh M. Khapra, Karthik Sankaranarayanan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose DuoRC, a novel dataset for Reading Comprehension (RC) that motivates several new challenges for neural approaches in language understanding beyond those offered by existing RC datasets. DuoRC contains 186,089 unique question-answer pairs created from a collection of 7680 pairs of movie plots where each pair in the collection reflects two versions of the same movie - one from Wikipedia and the other from IMDb - written by two different authors. We asked crowdsourced workers to create questions from one version of the plot and a different set of workers to extract or synthesize answers from the other version. This unique characteristic of DuoRC where questions and answers are created from different versions of a document narrating the same underlying story, ensures by design, that there is very little lexical overlap between the questions created from one version and the segments containing the answer in the other version. Further, since the two versions have different levels of plot detail, narration style, vocabulary, etc., answering questions from the second version requires deeper language understanding and incorporating external background knowledge. Additionally, the narrative style of passages arising from movie plots (as opposed to typical descriptive passages in existing datasets) exhibits the need to perform complex reasoning over events across multiple sentences. Indeed, we observe that state-of-the-art neural RC models which have achieved near human performance on the SQuAD dataset, even when coupled with traditional NLP techniques to address the challenges presented in DuoRC exhibit very poor performance (F1 score of 37.42% on DuoRC v/s 86% on SQuAD dataset). This opens up several interesting research avenues wherein DuoRC could complement other RC datasets to explore novel neural approaches for studying language understanding.

##### Abstract (translated by Google)
我们提出DuoRC，这是一种阅读理解（RC）的新颖数据集，它激发了除了现有RC数据集提供的语言理解的神经方法的几个新挑战。 DuoRC包含186809个独特的问答组合，这些组合由7680对电影地块集合创建，其中集合中的每一对都反映了两个不同作者编写的同一电影的两个版本 - 一个来自Wikipedia，另一个来自IMDb。我们要求众包工作者从一个版本的情节和一组不同的工作人员中提取问题，以从另一个版本中提取或综合答案。 DuoRC的这一独特特征，其中问题和答案是根据叙述相同底层故事的文档的不同版本创建的，通过设计确保从一个版本创建的问题与包含其他答案的片段之间几乎没有词汇重叠版。此外，由于两个版本具有不同层次的情节细节，叙述风格，词汇等，回答第二个版本的问题需要更深入的语言理解并结合外部背景知识。此外，从电影地块（与现有数据集中的典型描述性段落相对）产生的段落的叙述风格表现出需要对跨越多个句子的事件执行复杂的推理。事实上，我们观察到在SQUAD数据集上已经实现了接近人类表现的最先进的神经RC模型，即使与传统的NLP技术相结合以解决DuoRC中出现的挑战，其表现出非常差的表现（F1得分为37.42％在SQUAD数据集上DuoRC v / s 86％）。这开辟了一些有趣的研究途径，其中DuoRC可以补充其他RC数据集以探索用于研究语言理解的新型神经方法。

##### URL
[http://arxiv.org/abs/1804.07927](http://arxiv.org/abs/1804.07927)

##### PDF
[http://arxiv.org/pdf/1804.07927](http://arxiv.org/pdf/1804.07927)

