---
layout: post
title: "Patterns versus Characters in Subword-aware Neural Language Modeling"
date: 2017-09-02 07:00:22
categories: arXiv_CL
tags: arXiv_CL Regularization Embedding CNN Language_Model Relation
author: Rustem Takhanov, Zhenisbek Assylbekov
mathjax: true
---

* content
{:toc}

##### Abstract
Words in some natural languages can have a composite structure. Elements of this structure include the root (that could also be composite), prefixes and suffixes with which various nuances and relations to other words can be expressed. Thus, in order to build a proper word representation one must take into account its internal structure. From a corpus of texts we extract a set of frequent subwords and from the latter set we select patterns, i.e. subwords which encapsulate information on character $n$-gram regularities. The selection is made using the pattern-based Conditional Random Field model with $l_1$ regularization. Further, for every word we construct a new sequence over an alphabet of patterns. The new alphabet's symbols confine a local statistical context stronger than the characters, therefore they allow better representations in ${\mathbb{R}}^n$ and are better building blocks for word representation. In the task of subword-aware language modeling, pattern-based models outperform character-based analogues by 2-20 perplexity points. Also, a recurrent neural network in which a word is represented as a sum of embeddings of its patterns is on par with a competitive and significantly more sophisticated character-based convolutional architecture.

##### Abstract (translated by Google)
一些自然语言中的单词可以有一个复合结构。这个结构的元素包括根（也可以是复合的），前缀和后缀，可以用其表示各种细微差别和与其他词的关系。因此，为了建立一个合适的词汇表达，必须考虑到它的内部结构。从文本的语料库中，我们提取一组频繁的子词，并从后面的集合中选择模式，即封装字符$ n $ -gram规则性信息的子字。选择是使用$ l_1 $正则化的基于模式的条件随机场模型进行的。此外，对于每一个单词，我们都在一个模式字母表上构建一个新的序列。新的字母符号限制了一个比字符更强的局部统计上下文，因此它们允许在$ {\ mathbb {R}} ^ n $中更好的表示，并且对于字表示来说是更好的构建块。在子词感知语言建模的任务中，基于模式的模型以2-20个困惑点胜过基于字符的类似物。此外，一个循环的神经网络，其中一个词表示为其模式嵌入的总和与竞争性和更复杂的基于字符的卷积体系结构相当。

##### URL
[https://arxiv.org/abs/1709.00541](https://arxiv.org/abs/1709.00541)

##### PDF
[https://arxiv.org/pdf/1709.00541](https://arxiv.org/pdf/1709.00541)

