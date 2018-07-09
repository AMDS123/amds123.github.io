---
layout: post
title: "Neural Document Summarization by Jointly Learning to Score and Select Sentences"
date: 2018-07-06 08:15:15
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Qingyu Zhou, Nan Yang, Furu Wei, Shaohan Huang, Ming Zhou, Tiejun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Sentence scoring and sentence selection are two main steps in extractive document summarization systems. However, previous works treat them as two separated subtasks. In this paper, we present a novel end-to-end neural network framework for extractive document summarization by jointly learning to score and select sentences. It first reads the document sentences with a hierarchical encoder to obtain the representation of sentences. Then it builds the output summary by extracting sentences one by one. Different from previous methods, our approach integrates the selection strategy into the scoring model, which directly predicts the relative importance given previously selected sentences. Experiments on the CNN/Daily Mail dataset show that the proposed framework significantly outperforms the state-of-the-art extractive summarization models.

##### Abstract (translated by Google)
句子评分和句子选择是提取文档摘要系统中的两个主要步骤。但是，以前的作品将它们视为两个独立的子任务。在本文中，我们通过联合学习评分和选择句子，提出了一种新的端到端神经网络框架，用于提取文档摘要。它首先用分层编码器读取文档句子以获得句子的表示。然后通过逐句提取句子来构建输出摘要。与以前的方法不同，我们的方法将选择策略整合到评分模型中，评分模型直接预测给定先前选择的句子的相对重要性。在CNN / Daily Mail数据集上的实验表明，所提出的框架明显优于最先进的提取摘要模型。

##### URL
[http://arxiv.org/abs/1807.02305](http://arxiv.org/abs/1807.02305)

##### PDF
[http://arxiv.org/pdf/1807.02305](http://arxiv.org/pdf/1807.02305)

