---
layout: post
title: "Breaking the Softmax Bottleneck: A High-Rank RNN Language Model"
date: 2018-02-09 01:15:08
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model
author: Zhilin Yang, Zihang Dai, Ruslan Salakhutdinov, William W. Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate language modeling as a matrix factorization problem, and show that the expressiveness of Softmax-based models (including the majority of neural language models) is limited by a Softmax bottleneck. Given that natural language is highly context-dependent, this further implies that in practice Softmax with distributed word embeddings does not have enough capacity to model natural language. We propose a simple and effective method to address this issue, and improve the state-of-the-art perplexities on Penn Treebank and WikiText-2 to 47.69 and 40.68 respectively. The proposed method also excels on the large-scale 1B Word dataset, outperforming the baseline by over 5.6 points in perplexity.

##### Abstract (translated by Google)
我们将语言建模制定为矩阵分解问题，并且表明基于Softmax的模型（包括大多数神经语言模型）的表达受到Softmax瓶颈的限制。鉴于自然语言高度依赖于上下文，这进一步意味着在实践中使用分布式词嵌入的Softmax没有足够的能力来建模自然语言。我们提出了一个简单而有效的方法来解决这个问题，并将Penn Treebank和WikiText-2的最新困惑分别改善到47.69和40.68。所提出的方法在大规模的1BWORD数据集上也表现优异，超过基线的困惑度高出5.6个百分点。

##### URL
[http://arxiv.org/abs/1711.03953](http://arxiv.org/abs/1711.03953)

##### PDF
[http://arxiv.org/pdf/1711.03953](http://arxiv.org/pdf/1711.03953)

