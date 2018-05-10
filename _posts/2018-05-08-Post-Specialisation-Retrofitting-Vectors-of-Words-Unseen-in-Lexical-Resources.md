---
layout: post
title: "Post-Specialisation: Retrofitting Vectors of Words Unseen in Lexical Resources"
date: 2018-05-08 18:46:24
categories: arXiv_CL
tags: arXiv_CL Knowledge Tracking
author: Ivan Vuli&#x107;, Goran Glava&#x161;, Nikola Mrk&#x161;i&#x107;, Anna Korhonen
mathjax: true
---

* content
{:toc}

##### Abstract
Word vector specialisation (also known as retrofitting) is a portable, light-weight approach to fine-tuning arbitrary distributional word vector spaces by injecting external knowledge from rich lexical resources such as WordNet. By design, these post-processing methods only update the vectors of words occurring in external lexicons, leaving the representations of all unseen words intact. In this paper, we show that constraint-driven vector space specialisation can be extended to unseen words. We propose a novel post-specialisation method that: a) preserves the useful linguistic knowledge for seen words; while b) propagating this external signal to unseen words in order to improve their vector representations as well. Our post-specialisation approach explicits a non-linear specialisation function in the form of a deep neural network by learning to predict specialised vectors from their original distributional counterparts. The learned function is then used to specialise vectors of unseen words. This approach, applicable to any post-processing model, yields considerable gains over the initial specialisation models both in intrinsic word similarity tasks, and in two downstream tasks: dialogue state tracking and lexical text simplification. The positive effects persist across three languages, demonstrating the importance of specialising the full vocabulary of distributional word vector spaces.

##### Abstract (translated by Google)
Word矢量专业化（也称为翻新）是一种便携式轻量级方法，可通过从WordNet等丰富的词汇资源中注入外部知识来微调任意分布式词向量空间。通过设计，这些后处理方法仅更新外部词典中出现的单词的矢量，使所有看不见的单词的表示保持完好。在本文中，我们展示了约束驱动的向量空间专业化可以扩展到看不见的单词。我们提出了一种新颖的专业化后的方法：a）保留有用的语言知识，为所看到的单词;同时b）将这个外部信号传播到看不见的单词以改善它们的向量表示。我们的专业化后处理方法通过学习从其原始分布对应物中预测专用向量来以深度神经网络的形式阐明非线性专业化函数。学过的函数然后被用来专门化看不见的单词的向量。这种方法适用于任何后处理模型，与初始专业化模型相比，内部词相似任务和两个下游任务（对话状态跟踪和词汇文本简化）产生了相当大的收益。这种积极效果在三种语言中持续存在，证明了专门分配词向量空间的全部词汇的重要性。

##### URL
[http://arxiv.org/abs/1805.03228](http://arxiv.org/abs/1805.03228)

##### PDF
[http://arxiv.org/pdf/1805.03228](http://arxiv.org/pdf/1805.03228)

