---
layout: post
title: "Dynamic Compositionality in Recursive Neural Networks with Structure-aware Tag Representations"
date: 2018-09-07 02:59:42
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Inference RNN
author: Taeuk Kim, Jihun Choi, Daniel Edmiston, Sanghwan Bae, Sang-goo Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing recursive neural network (RvNN) architectures utilize only the structure of parse trees, ignoring syntactic tags which are provided as by-products of parsing. We present a novel RvNN architecture that can provide dynamic compositionality by considering comprehensive syntactic information derived from both the structure and linguistic tags. Specifically, we introduce a structure-aware tag representation constructed by a separate tag-level tree-LSTM. With this, we can control the composition function of the existing word-level tree-LSTM by augmenting the representation as a supplementary input to the gate functions of the tree-LSTM. We show that models built upon the proposed architecture obtain superior performance on several sentence-level tasks such as sentiment analysis and natural language inference when compared against previous tree-structured models and other sophisticated neural models. In particular, our models achieve new state-of-the-art results on Stanford Sentiment Treebank, Movie Review, and Text Retrieval Conference datasets.

##### Abstract (translated by Google)
大多数现有的递归神经网络（RvNN）架构仅利用解析树的结构，忽略作为解析的副产品提供的句法标签。我们提出了一种新颖的RvNN架构，它可以通过考虑从结构和语言标签中得到的综合句法信息来提供动态组合。具体来说，我们引入了由单独的标记级树LSTM构造的结构感知标记表示。这样，我们可以通过增加表示作为树-LSTM的门函数的补充输入来控制现有字级树-LSTM的组合函数。我们表明，与先前的树形结构模型和其他复杂的神经模型进行比较，建立在所提出的体系结构上的模型在几个句子级任务（例如情感分析和自然语言推理）中获得了优越的性能。特别是，我们的模型在斯坦福情感树库，电影评论和文本检索会议数据集上实现了最新的最新成果。

##### URL
[https://arxiv.org/abs/1809.02286](https://arxiv.org/abs/1809.02286)

##### PDF
[https://arxiv.org/pdf/1809.02286](https://arxiv.org/pdf/1809.02286)

