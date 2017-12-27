---
layout: post
title: "Dual Long Short-Term Memory Networks for Sub-Character Representation Learning"
date: 2017-12-23 21:12:23
categories: arXiv_CL
tags: arXiv_CL Knowledge Segmentation Embedding Represenation_Learning RNN Memory_Networks
author: He Han, Yang Xiaokun, Wu Lei, Yan Hua, Gao Zhimin, Feng Yi, Townsend George
mathjax: true
---

* content
{:toc}

##### Abstract
Characters have commonly been regarded as the minimal processing unit in Natural Language Processing (NLP). But many non-latin languages have hieroglyphic writing systems, involving a big alphabet with thousands or millions of characters. Each character is composed of even smaller parts, which are often ignored by the previous work. In this paper, we propose a novel architecture employing two stacked Long Short-Term Memory Networks (LSTMs) to learn sub-character level representation and capture deeper level of semantic meanings. To build a concrete study and substantiate the efficiency of our neural architecture, we take Chinese Word Segmentation as a research case example. Among those languages, Chinese is a typical case, for which every character contains several components called radicals. Our networks employ a shared radical level embedding to solve both Simplified and Traditional Chinese Word Segmentation, without extra Traditional to Simplified Chinese conversion, in such a highly end-to-end way the word segmentation can be significantly simplified compared to the previous work. Radical level embeddings can also capture deeper semantic meaning below character level and improve the system performance of learning. By tying radical and character embeddings together, the parameter count is reduced whereas semantic knowledge is shared and transferred between two levels, boosting the performance largely. On 3 out of 4 Bakeoff 2005 datasets, our method surpassed state-of-the-art results by up to 0.4%. Our results are reproducible, source codes and corpora are available on GitHub.

##### Abstract (translated by Google)
字符通常被认为是自然语言处理（NLP）中的最小处理单元。但是许多非拉丁语言都有象形文字的书写系统，涉及一个有数千或数百万字符的大字母表。每个角色都是由更小的部分组成的，这在以前的工作中经常被忽略。在本文中，我们提出了一个新的架构，采用两个堆叠的长时短记忆网络（LSTMs）来学习子字符级别的表示，并捕获更深层次的语义。为了建立一个具体的研究结果和证实我们的神经结构的效率，我们把中文分词作为一个研究案例。在这些语言中，汉语是一个典型的例子，每个汉字都包含几个组成部分，即部首。我们的网络使用共享的基本级别嵌入来解决简化和繁体中文分词，而不需要额外的繁体到简体中文转换，以这种高度端到端的方式，与先前的工作相比，分词可以被显着地简化。激进水平嵌入还可以在字符级别下捕获更深的语义，提高系统的学习性能。通过将激进和字符嵌入在一起，减少了参数数量，而语义知识在两个层次之间共享和转移，大大提高了性能。在4个Bakeoff 2005数据集中的3个中，我们的方法超过最新的结果高达0.4％。我们的结果是可重现的，源代码和语料库在GitHub上可用。

##### URL
[http://arxiv.org/abs/1712.08841](http://arxiv.org/abs/1712.08841)

##### PDF
[http://arxiv.org/pdf/1712.08841](http://arxiv.org/pdf/1712.08841)

