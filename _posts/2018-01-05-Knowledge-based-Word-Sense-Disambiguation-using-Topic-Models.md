---
layout: post
title: "Knowledge-based Word Sense Disambiguation using Topic Models"
date: 2018-01-05 19:20:24
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Devendra Singh Chaplot, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
Word Sense Disambiguation is an open problem in Natural Language Processing which is particularly challenging and useful in the unsupervised setting where all the words in any given text need to be disambiguated without using any labeled data. Typically WSD systems use the sentence or a small window of words around the target word as the context for disambiguation because their computational complexity scales exponentially with the size of the context. In this paper, we leverage the formalism of topic model to design a WSD system that scales linearly with the number of words in the context. As a result, our system is able to utilize the whole document as the context for a word to be disambiguated. The proposed method is a variant of Latent Dirichlet Allocation in which the topic proportions for a document are replaced by synset proportions. We further utilize the information in the WordNet by assigning a non-uniform prior to synset distribution over words and a logistic-normal prior for document distribution over synsets. We evaluate the proposed method on Senseval-2, Senseval-3, SemEval-2007, SemEval-2013 and SemEval-2015 English All-Word WSD datasets and show that it outperforms the state-of-the-art unsupervised knowledge-based WSD system by a significant margin.

##### Abstract (translated by Google)
词义消歧是自然语言处理中的一个未解决的问题，在无监督设置中特别具有挑战性和有用性，其中在任何给定文本中的所有单词都需要在不使用任何标记数据的情况下被消除歧义。通常，WSD系统使用围绕目标词语的句子或小窗口作为消歧的上下文，因为它们的计算复杂性随着上下文的大小成指数地变化。在本文中，我们利用主题模型的形式来设计一个WSD系统，该系统与上下文中的词数成线性关系。因此，我们的系统能够利用整个文档作为一个单词的上下文来消除歧义。所提出的方法是Latent Dirichlet Allocation的变体，其中文档的主题比例被synset比例代替。我们进一步利用WordNet中的信息，通过在词汇上的synset分配之前分配不均匀的分配，并且在synsets上分配文档分配之前的逻辑正常。我们评估了Senseval-2，Senseval-3，SemEval-2007，SemEval-2013和SemEval-2015英文全文WSD数据集上的方法，并表明它优于最先进的无监督知识型WSD系统相当大的幅度。

##### URL
[http://arxiv.org/abs/1801.01900](http://arxiv.org/abs/1801.01900)

##### PDF
[http://arxiv.org/pdf/1801.01900](http://arxiv.org/pdf/1801.01900)

