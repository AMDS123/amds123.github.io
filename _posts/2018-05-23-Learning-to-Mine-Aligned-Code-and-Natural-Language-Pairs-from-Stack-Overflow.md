---
layout: post
title: "Learning to Mine Aligned Code and Natural Language Pairs from Stack Overflow"
date: 2018-05-23 03:39:04
categories: arXiv_CL
tags: arXiv_CL Summarization Relation
author: Pengcheng Yin, Bowen Deng, Edgar Chen, Bogdan Vasilescu, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
For tasks like code synthesis from natural language, code retrieval, and code summarization, data-driven models have shown great promise. However, creating these models require parallel data between natural language (NL) and code with fine-grained alignments. Stack Overflow (SO) is a promising source to create such a data set: the questions are diverse and most of them have corresponding answers with high-quality code snippets. However, existing heuristic methods (e.g., pairing the title of a post with the code in the accepted answer) are limited both in their coverage and the correctness of the NL-code pairs obtained. In this paper, we propose a novel method to mine high-quality aligned data from SO using two sets of features: hand-crafted features considering the structure of the extracted snippets, and correspondence features obtained by training a probabilistic model to capture the correlation between NL and code using neural networks. These features are fed into a classifier that determines the quality of mined NL-code pairs. Experiments using Python and Java as test beds show that the proposed method greatly expands coverage and accuracy over existing mining methods, even when using only a small number of labeled examples. Further, we find that reasonable results are achieved even when training the classifier on one language and testing on another, showing promise for scaling NL-code mining to a wide variety of programming languages beyond those for which we are able to annotate data.

##### Abstract (translated by Google)
对于像自然语言代码合成，代码检索和代码汇总这样的任务，数据驱动的模型已经显示出很大的希望。但是，创建这些模型需要在自然语言（NL）和具有细粒度对齐的代码之间的并行数据。堆栈溢出（SO）是创建这样一个数据集的有希望的来源：这些问题是多种多样的，其中大多数都有高质量代码片段的相应答案。然而，现有的启发式方法（例如，将帖子的标题与接受的答案中的代码配对）在其覆盖范围和所获得的NL-码对的正确性方面都受到限制。在本文中，我们提出了一种新方法来从SO中挖掘出高质量的对齐数据，其中使用了两组特征：考虑提取片段的结构的手工特征以及通过训练概率模型获得的对应特征以捕获NL和使用神经网络的代码。这些特征被馈送到确定所挖掘的NL-码对的质量的分类器中。使用Python和Java作为测试平台的实验表明，与现有挖掘方法相比，所提出的方法大大扩展了覆盖范围和精度，即使仅使用少量标记示例。此外，我们发现，即使在一种语言上训练分类器并在另一种语言上进行测试时，也可以获得合理的结果，这显示了将NL-code挖掘扩展到除我们能够注释数据以外的各种编程语言的承诺。

##### URL
[http://arxiv.org/abs/1805.08949](http://arxiv.org/abs/1805.08949)

##### PDF
[http://arxiv.org/pdf/1805.08949](http://arxiv.org/pdf/1805.08949)

