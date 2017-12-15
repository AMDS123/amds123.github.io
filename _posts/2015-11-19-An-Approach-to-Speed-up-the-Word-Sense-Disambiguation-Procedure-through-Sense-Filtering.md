---
layout: post
title: "An Approach to Speed-up the Word Sense Disambiguation Procedure through Sense Filtering"
date: 2015-11-19 11:29:10
categories: arXiv_CL
tags: arXiv_CL
author: Alok Ranjan Pal, Anupam Munshi, Diganta Saha
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we are going to focus on speed up of the Word Sense Disambiguation procedure by filtering the relevant senses of an ambiguous word through Part-of-Speech Tagging. First, this proposed approach performs the Part-of-Speech Tagging operation before the disambiguation procedure using Bigram approximation. As a result, the exact Part-of-Speech of the ambiguous word at a particular text instance is derived. In the next stage, only those dictionary definitions (glosses) are retrieved from an online dictionary, which are associated with that particular Part-of-Speech to disambiguate the exact sense of the ambiguous word. In the training phase, we have used Brown Corpus for Part-of-Speech Tagging and WordNet as an online dictionary. The proposed approach reduces the execution time upto half (approximately) of the normal execution time for a text, containing around 200 sentences. Not only that, we have found several instances, where the correct sense of an ambiguous word is found for using the Part-of-Speech Tagging before the Disambiguation procedure.

##### Abstract (translated by Google)
在本文中，我们将着重于通过词性标注来过滤歧义词的相关含义来加快词义消歧过程。首先，这个提出的方法使用Bigram近似在消歧过程之前执行词类标记操作。结果，导出了在特定文本实例处的歧义词的精确词性。在下一个阶段，只有从在线词典中检索到那些与该特定词类相关联的词典定义（光晕）才能消除歧义词的确切含义。在训练阶段，我们使用布朗语料库进行词性标记，并使用WordNet作为在线词典。所提出的方法将执行时间减少到包含大约200个句子的文本的正常执行时间的一半（大约）。不仅如此，我们还发现了几个实例，在消歧过程之前发现了使用词性标注的歧义词的正确含义。

##### URL
[https://arxiv.org/abs/1610.06601](https://arxiv.org/abs/1610.06601)

##### PDF
[https://arxiv.org/pdf/1610.06601](https://arxiv.org/pdf/1610.06601)

