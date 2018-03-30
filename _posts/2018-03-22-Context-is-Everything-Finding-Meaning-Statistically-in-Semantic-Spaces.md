---
layout: post
title: "Context is Everything: Finding Meaning Statistically in Semantic Spaces"
date: 2018-03-22 17:54:21
categories: arXiv_CL
tags: arXiv_CL Embedding Transfer_Learning Detection Relation
author: Eric Zelikman
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a simple and explicit measure of word importance in a global context, including very small contexts (10+ sentences). After generating a word-vector space containing both 2-gram clauses and single tokens, it became clear that more contextually significant words disproportionately define clause meanings. Using this simple relationship in a weighted bag-of-words sentence embedding model results in sentence vectors that outperform the state-of-the-art for subjectivity/objectivity analysis, as well as paraphrase detection, and fall within those produced by state-of-the-art models for six other transfer learning tests. The metric was then extended to a sentence/document summarizer, an improved (and context-aware) cosine distance and a simple document stop word identifier. The sigmoid-global context weighted bag of words is presented as a new baseline for sentence embeddings.

##### Abstract (translated by Google)
本文在全球范围内引入了一个简单明确的单词重要度量，包括非常小的语境（10+句子）。在生成包含2克语句和单个令牌的单词向量空间之后，很明显，更多的内容有意义的单词不成比例地定义了语句的含义。在一个加权词袋句子嵌入模型中使用这种简单的关系可以得到比主观性/客观性分析以及释义检测更为优越的语句向量，并且落入由状态为其他六个转换学习测试提供最先进的模型。然后将度量扩展到句子/文档汇总器，改进的（和上下文感知的）余弦距离和简单的文档停用词标识符。将S形全局上下文加权的单词袋表示为语句嵌入的新基线。

##### URL
[https://arxiv.org/abs/1803.08493](https://arxiv.org/abs/1803.08493)

##### PDF
[https://arxiv.org/pdf/1803.08493](https://arxiv.org/pdf/1803.08493)

