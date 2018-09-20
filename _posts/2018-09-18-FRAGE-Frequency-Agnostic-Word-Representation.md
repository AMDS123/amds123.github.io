---
layout: post
title: "FRAGE: Frequency-Agnostic Word Representation"
date: 2018-09-18 13:31:22
categories: arXiv_CL
tags: arXiv_CL Adversarial Text_Classification Embedding Classification Language_Model
author: Chengyue Gong, Di He, Xu Tan, Tao Qin, Liwei Wang, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Continuous word representation (aka word embedding) is a basic building block in many neural network-based models used in natural language processing tasks. Although it is widely accepted that words with similar semantics should be close to each other in the embedding space, we find that word embeddings learned in several tasks are biased towards word frequency: the embeddings of high-frequency and low-frequency words lie in different subregions of the embedding space, and the embedding of a rare word and a popular word can be far from each other even if they are semantically similar. This makes learned word embeddings ineffective, especially for rare words, and consequently limits the performance of these neural network models. In this paper, we develop a neat, simple yet effective way to learn \emph{FRequency-AGnostic word Embedding} (FRAGE) using adversarial training. We conducted comprehensive studies on ten datasets across four natural language processing tasks, including word similarity, language modeling, machine translation and text classification. Results show that with FRAGE, we achieve higher performance than the baselines in all tasks.

##### Abstract (translated by Google)
连续字表示（又名字嵌入）是在自然语言处理任务中使用的许多基于神经网络的模型中的基本构建块。尽管人们普遍认为具有相似语义的词在嵌入空间中应该彼此接近，但我们发现在几个任务中学习的词嵌入偏向于词频：高频和低频词的嵌入在于不同嵌入空间的子区域，以及罕见词和流行词的嵌入可以彼此相距很远，即使它们在语义上相似。这使得学习的单词嵌入无效，特别是对于罕见的单词，因此限制了这些神经网络模型的性能。在本文中，我们开发了一种简洁而有效的方法来学习\ emph {FRequency-Agnostic word Embedding}（FRAGE），使用对抗训练。我们对四个自然语言处理任务的十个数据集进行了全面的研究，包括单词相似度，语言建模，机器翻译和文本分类。结果表明，使用FRAGE，我们在所有任务中都获得了比基线更高的性能。

##### URL
[http://arxiv.org/abs/1809.06858](http://arxiv.org/abs/1809.06858)

##### PDF
[http://arxiv.org/pdf/1809.06858](http://arxiv.org/pdf/1809.06858)

