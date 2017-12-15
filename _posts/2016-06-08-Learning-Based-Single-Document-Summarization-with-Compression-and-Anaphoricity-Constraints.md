---
layout: post
title: "Learning-Based Single-Document Summarization with Compression and Anaphoricity Constraints"
date: 2016-06-08 05:39:10
categories: arXiv_SD
tags: arXiv_SD Sparse Summarization
author: Greg Durrett, Taylor Berg-Kirkpatrick, Dan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
We present a discriminative model for single-document summarization that integrally combines compression and anaphoricity constraints. Our model selects textual units to include in the summary based on a rich set of sparse features whose weights are learned on a large corpus. We allow for the deletion of content within a sentence when that deletion is licensed by compression rules; in our framework, these are implemented as dependencies between subsentential units of text. Anaphoricity constraints then improve cross-sentence coherence by guaranteeing that, for each pronoun included in the summary, the pronoun's antecedent is included as well or the pronoun is rewritten as a full mention. When trained end-to-end, our final system outperforms prior work on both ROUGE as well as on human judgments of linguistic quality.

##### Abstract (translated by Google)
我们提出了一个单一的文件摘要鉴别模型，整合压缩和照应性约束。我们的模型基于丰富的稀疏特征来选择文本单元以包括在摘要中，其中稀疏特征的权重是在大型语料库上学习的。当删除被压缩规则许可时，我们允许删除句子中的内容。在我们的框架中，这些被实现为文本的次级单元之间的依赖关系。通过保证隐喻约束，通过保证对于包括在概要中的每个代词，代词的先行词被包括在内，或者代词被重写为一个完整的提及，来改善交叉句子的连贯性。在端到端的训练中，我们的最终系统比ROUGE以及人类对语言质量的判断都要优胜。

##### URL
[https://arxiv.org/abs/1603.08887](https://arxiv.org/abs/1603.08887)

##### PDF
[https://arxiv.org/pdf/1603.08887](https://arxiv.org/pdf/1603.08887)

