---
layout: post
title: "Classifying Idiomatic and Literal Expressions Using Topic Models and Intensity of Emotions"
date: 2018-02-27 15:20:43
categories: arXiv_CL
tags: arXiv_CL Classification Detection
author: Jing Peng, Anna Feldman, Ekaterina Vylomova
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an algorithm for automatic classification of idiomatic and literal expressions. Our starting point is that words in a given text segment, such as a paragraph, that are highranking representatives of a common topic of discussion are less likely to be a part of an idiomatic expression. Our additional hypothesis is that contexts in which idioms occur, typically, are more affective and therefore, we incorporate a simple analysis of the intensity of the emotions expressed by the contexts. We investigate the bag of words topic representation of one to three paragraphs containing an expression that should be classified as idiomatic or literal (a target phrase). We extract topics from paragraphs containing idioms and from paragraphs containing literals using an unsupervised clustering method, Latent Dirichlet Allocation (LDA) (Blei et al., 2003). Since idiomatic expressions exhibit the property of non-compositionality, we assume that they usually present different semantics than the words used in the local topic. We treat idioms as semantic outliers, and the identification of a semantic shift as outlier detection. Thus, this topic representation allows us to differentiate idioms from literals using local semantic contexts. Our results are encouraging.

##### Abstract (translated by Google)
我们描述了一种自动分类惯用和文字表达式的算法。我们的出发点是，给定文本片段中的文字（如段落）是常见讨论话题的高级代表，因此不太可能成为惯用表达的一部分。我们的另一个假设是，习语发生的语境通常更具情感性，因此，我们对语境表达的情绪强度进行简单分析。我们调查了包含应该被分类为习惯用语或文字（目标短语）的表达的一到三个段落的单词包话题表示。我们使用无监督聚类方法，Latent Dirichlet Allocation（LDA）（Blei et al。，2003）从包含成语的段落和包含文字的段落中提取主题。由于惯用表达式表现出非组合性，我们假设它们通常表现出与本地主题中使用的单词不同的语义。我们把成语看作是语义异常值，并把语义转换看作异常值检测。因此，这个主题表示允许我们使用本地语义上下文来区分成语和文字。我们的结果令人鼓舞。

##### URL
[https://arxiv.org/abs/1802.09961](https://arxiv.org/abs/1802.09961)

##### PDF
[https://arxiv.org/pdf/1802.09961](https://arxiv.org/pdf/1802.09961)

