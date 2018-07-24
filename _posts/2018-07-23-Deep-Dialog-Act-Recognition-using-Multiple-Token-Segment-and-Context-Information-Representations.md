---
layout: post
title: "Deep Dialog Act Recognition using Multiple Token, Segment, and Context Information Representations"
date: 2018-07-23 13:12:28
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model Recognition
author: Eug&#xe9;nio Ribeiro, Ricardo Ribeiro, David Martins de Matos
mathjax: true
---

* content
{:toc}

##### Abstract
A dialog act is a representation of an intention transmitted in the form of words. In this sense, when someone wants to transmit some intention, it is revealed both in the selected words and in how they are combined to form a structured segment. Furthermore, the intentions of a speaker depend not only on her intrinsic motivation, but also on the history of the dialog and the expectation she has of its future. In this article we explore multiple representation approaches to capture cues for intention at different levels. Recent approaches on automatic dialog act recognition use Word2Vec embeddings for word representation. However, these are not able to capture segment structure information nor morphological traits related to intention. Thus, we also explore the use of dependency-based word embeddings, as well as character-level tokenization. To generate the segment representation, the top performing approaches on the task use either RNNs that are able to capture information concerning the sequentiality of the tokens or CNNs that are able to capture token patterns that reveal function. However, both aspects are important and should be captured together. Thus, we also explore the use of an RCNN. Finally, context information concerning turn-taking, as well as that provided by the surrounding segments has been proved important in previous studies. However, the representation approaches used for the latter in those studies are not appropriate to capture sequentiality, which is one of the most important characteristics of the segments in a dialog. Thus, we explore the use of approaches able to capture that information. By combining the best approaches for each aspect, we achieve results that surpass the previous state-of-the-art in a dialog system context and similar to human-level in an annotation context on the Switchboard Dialog Act Corpus, which is the most explored corpus for the task.

##### Abstract (translated by Google)
对话行为是以单词形式传递的意图的表示。从这个意义上讲，当某人想要传达一些意图时，它会在选定的单词中以及如何组合形成结构化的片段中显示出来。此外，说话者的意图不仅取决于她的内在动机，还取决于对话的历史和对未来的期望。在本文中，我们将探索多种表示方法，以捕获不同级别的意图提示。最近关于自动对话动作识别的方法使用Word2Vec嵌入来进行单词表示。然而，这些不能捕获分段结构信息或与意图相关的形态特征。因此，我们还探讨了基于依赖的词嵌入的使用，以及字符级标记化。为了生成片段表示，关于任务的最佳执行方法使用能够捕获关于令牌的序列性的信息的RNN或能够捕获揭示功能的令牌模式的CNN。但是，这两个方面都很重要，应该一起捕获。因此，我们还探讨了RCNN的使用。最后，有关轮换的背景信息以及周围环节提供的信息已被证明在以前的研究中很重要。然而，在这些研究中用于后者的表示方法不适合捕获序列性，这是对话中段的最重要特征之一。因此，我们探索了能够捕获该信息的方法的使用。通过结合每个方面的最佳方法，我们在对话框系统上下文中实现了超越先前技术水平的结果，并且在Switchboard Dialog Act Corpus的注释上下文中类似于人类级别，这是最受探索的语料库的任务。

##### URL
[http://arxiv.org/abs/1807.08587](http://arxiv.org/abs/1807.08587)

##### PDF
[http://arxiv.org/pdf/1807.08587](http://arxiv.org/pdf/1807.08587)

