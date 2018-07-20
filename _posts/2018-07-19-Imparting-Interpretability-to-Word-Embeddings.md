---
layout: post
title: "Imparting Interpretability to Word Embeddings"
date: 2018-07-19 08:14:59
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: Aykut Koç, İhsan Utlu, Lutfi Kerem Senel, Haldun M. Ozaktas
mathjax: true
---

* content
{:toc}

##### Abstract
As an ubiquitous method in natural language processing, word embeddings are extensively employed to map semantic properties of words into a dense vector representation. They capture semantic and syntactic relations among words but the vector corresponding to the words are only meaningful relative to each other. Neither the vector nor its dimensions have any absolute, interpretable meaning. We introduce an additive modification to the objective function of the embedding learning algorithm that encourages the embedding vectors of words that are semantically related a predefined concept to take larger values along a specified dimension, while leaving the original semantic learning mechanism mostly unaffected. In other words, we align words that are already determined to be related, along predefined concepts. Therefore, we impart interpretability to the word embedding by assigning meaning to its vector dimensions. The predefined concepts are derived from an external lexical resource, which in this paper is chosen as Roget's Thesaurus. We observe that alignment along the chosen concepts is not limited to words in the Thesaurus and extends to other related words as well. We quantify the extent of interpretability and assignment of meaning from our experimental results. We also demonstrate the preservation of semantic coherence of the resulting vector space by using word-analogy and word-similarity tests. These tests show that the interpretability-imparted word embeddings that are obtained by the proposed framework do not sacrifice performances in common benchmark tests.

##### Abstract (translated by Google)
作为自然语言处理中普遍使用的方法，广泛使用单词嵌入来将单词的语义属性映射到密集向量表示中。它们捕获单词之间的语义和句法关系，但对应于单词的向量仅相对于彼此有意义。矢量及其维度都没有任何绝对的，可解释的含义。我们引入了对嵌入学习算法的目标函数的加性修改，其鼓励与预定义概念在语义上相关的词的嵌入向量沿着指定维度获取更大的值，同时使原始语义学习机制基本上不受影响。换句话说，我们沿着预定义的概念对齐已经确定为相关的单词。因此，我们通过为其向量维度赋予意义来赋予嵌入一词的可解释性。预定义概念源自外部词汇资源，在本文中，它被选为Roget的同义词库。我们观察到所选概念的对齐不仅限于同义词库中的单词，也扩展到其他相关单词。我们从实验结果中量化了可解释性和意义分配的程度。我们还通过使用单词类比和单词相似性测试来证明保留所得向量空间的语义连贯性。这些测试表明，通过提出的框架获得的可解释性赋予的单词嵌入不会牺牲常见基准测试中的性能。

##### URL
[https://arxiv.org/abs/1807.07279](https://arxiv.org/abs/1807.07279)

##### PDF
[https://arxiv.org/pdf/1807.07279](https://arxiv.org/pdf/1807.07279)

