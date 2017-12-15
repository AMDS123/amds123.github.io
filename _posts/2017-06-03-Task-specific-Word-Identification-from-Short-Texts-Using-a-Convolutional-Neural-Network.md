---
layout: post
title: "Task-specific Word Identification from Short Texts Using a Convolutional Neural Network"
date: 2017-06-03 02:15:44
categories: arXiv_CL
tags: arXiv_CL Sentiment Review CNN Classification Detection
author: Shuhan Yuan, Xintao Wu, Yang Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
Task-specific word identification aims to choose the task-related words that best describe a short text. Existing approaches require well-defined seed words or lexical dictionaries (e.g., WordNet), which are often unavailable for many applications such as social discrimination detection and fake review detection. However, we often have a set of labeled short texts where each short text has a task-related class label, e.g., discriminatory or non-discriminatory, specified by users or learned by classification algorithms. In this paper, we focus on identifying task-specific words and phrases from short texts by exploiting their class labels rather than using seed words or lexical dictionaries. We consider the task-specific word and phrase identification as feature learning. We train a convolutional neural network over a set of labeled texts and use score vectors to localize the task-specific words and phrases. Experimental results on sentiment word identification show that our approach significantly outperforms existing methods. We further conduct two case studies to show the effectiveness of our approach. One case study on a crawled tweets dataset demonstrates that our approach can successfully capture the discrimination-related words/phrases. The other case study on fake review detection shows that our approach can identify the fake-review words/phrases.

##### Abstract (translated by Google)
任务特定的单词识别旨在选择最能描述短文本的任务相关单词。现有的方法需要明确定义的种子词或词典（例如WordNet），这些词通常不能用于许多应用，例如社会歧视检测和假检查检测。然而，我们经常有一组标记的短文本，其中每个短文本具有任务相关的类别标签，例如由用户指定或由分类算法学习的歧视性或非歧视性的。在本文中，我们通过利用他们的类标签而不是使用种子词或词典来识别短文本中特定于任务的单词和短语。我们认为任务特定的词和词组识别是特征学习。我们训练卷积神经网络的一套标签文本，并使用分数向量本地化任务特定的单词和短语。情感词识别的实验结果表明，我们的方法明显优于现有的方法。我们进一步进行两个案例研究来展示我们的方法的有效性。一个关于抓取的推文数据集的案例研究表明，我们的方法可以成功捕获与歧视有关的单词/短语。另一个关于假检查检测的案例研究表明，我们的方法可以识别假检讨的单词/短语。

##### URL
[https://arxiv.org/abs/1706.00884](https://arxiv.org/abs/1706.00884)

##### PDF
[https://arxiv.org/pdf/1706.00884](https://arxiv.org/pdf/1706.00884)

