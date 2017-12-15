---
layout: post
title: "Learning Similarity Functions for Pronunciation Variations"
date: 2017-06-18 11:52:54
categories: arXiv_SD
tags: arXiv_SD Face Speech_Recognition RNN Classification Recognition
author: Einat Naaman, Yossi Adi, Joseph Keshet
mathjax: true
---

* content
{:toc}

##### Abstract
A significant source of errors in Automatic Speech Recognition (ASR) systems is due to pronunciation variations which occur in spontaneous and conversational speech. Usually ASR systems use a finite lexicon that provides one or more pronunciations for each word. In this paper, we focus on learning a similarity function between two pronunciations. The pronunciations can be the canonical and the surface pronunciations of the same word or they can be two surface pronunciations of different words. This task generalizes problems such as lexical access (the problem of learning the mapping between words and their possible pronunciations), and defining word neighborhoods. It can also be used to dynamically increase the size of the pronunciation lexicon, or in predicting ASR errors. We propose two methods, which are based on recurrent neural networks, to learn the similarity function. The first is based on binary classification, and the second is based on learning the ranking of the pronunciations. We demonstrate the efficiency of our approach on the task of lexical access using a subset of the Switchboard conversational speech corpus. Results suggest that on this task our methods are superior to previous methods which are based on graphical Bayesian methods.

##### Abstract (translated by Google)
自动语音识别（ASR）系统中的一个重要的错误来源是自发和对话式语音中发生的发音变化。通常ASR系统使用一个有限的词典，为每个单词提供一个或多个发音。在本文中，我们着重于学习两个发音之间的相似性函数。发音可以是同一个单词的规范和表面发音，也可以是不同单词的两个表面发音。这个任务概括了词汇访问（学习单词之间的映射问题及其可能的发音的问题）和定义单词邻域等问题。它也可以用来动态增加发音词典的大小，或者用于预测ASR错误。我们提出了两种基于递归神经网络的方法来学习相似函数。一是基于二进制分类，二是基于学习发音的排序。我们证明了我们的方法在使用交换机对话语料库子集的词汇访问任务上的效率。结果表明，在这个任务上，我们的方法优于基于图形贝叶斯方法的以前的方法。

##### URL
[https://arxiv.org/abs/1703.09817](https://arxiv.org/abs/1703.09817)

##### PDF
[https://arxiv.org/pdf/1703.09817](https://arxiv.org/pdf/1703.09817)

