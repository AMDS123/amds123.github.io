---
layout: post
title: "LightRNN: Memory and Computation-Efficient Recurrent Neural Networks"
date: 2016-10-31 12:24:13
categories: arXiv_CV
tags: arXiv_CV Embedding RNN Language_Model
author: Xiang Li, Tao Qin, Jian Yang, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have achieved state-of-the-art performances in many natural language processing tasks, such as language modeling and machine translation. However, when the vocabulary is large, the RNN model will become very big (e.g., possibly beyond the memory capacity of a GPU device) and its training will become very inefficient. In this work, we propose a novel technique to tackle this challenge. The key idea is to use 2-Component (2C) shared embedding for word representations. We allocate every word in the vocabulary into a table, each row of which is associated with a vector, and each column associated with another vector. Depending on its position in the table, a word is jointly represented by two components: a row vector and a column vector. Since the words in the same row share the row vector and the words in the same column share the column vector, we only need $2 \sqrt{|V|}$ vectors to represent a vocabulary of $|V|$ unique words, which are far less than the $|V|$ vectors required by existing approaches. Based on the 2-Component shared embedding, we design a new RNN algorithm and evaluate it using the language modeling task on several benchmark datasets. The results show that our algorithm significantly reduces the model size and speeds up the training process, without sacrifice of accuracy (it achieves similar, if not better, perplexity as compared to state-of-the-art language models). Remarkably, on the One-Billion-Word benchmark Dataset, our algorithm achieves comparable perplexity to previous language models, whilst reducing the model size by a factor of 40-100, and speeding up the training process by a factor of 2. We name our proposed algorithm \emph{LightRNN} to reflect its very small model size and very high training speed.

##### Abstract (translated by Google)
递归神经网络（RNN）已经在许多自然语言处理任务（例如语言建模和机器翻译）中获得了最先进的性能。然而，当词汇量很大时，RNN模型将变得非常大（例如，可能超出GPU设备的存储容量），并且其训练将变得非常低效。在这项工作中，我们提出了一种新的技术来解决这个挑战。关键的想法是使用双分量（2C）共享嵌入的词表示。我们将词汇表中的每个单词分配到一个表中，每一行与一个向量相关联，每一列与另一个向量相关联。根据它在表格中的位置，一个单词由两个组件联合表示：行向量和列向量。由于同一行中的单词共享行向量，同一列中的单词共享列向量，因此我们只需要$ 2 \ sqrt {| V |} $个向量来表示$ | V | $个单词的词汇表，远低于现有方法所要求的$ | V | $向量。基于二分量共享嵌入，我们设计了一种新的RNN算法，并使用多个基准数据集上的语言建模任务对其进行评估。结果表明，我们的算法显着减少了模型的大小，加快了训练过程，而不牺牲精确性（与最先进的语言模型相比，它实现了类似的，即使不是更好的困惑）。值得注意的是，在十亿字基准数据集上，我们的算法实现了与之前的语言模型相似的困惑，同时将模型尺寸缩小了40-100倍，并且加快了培训过程2倍。提出的算法\ emph {LightRNN}来反映其非常小的模型大小和非常高的训练速度。

##### URL
[https://arxiv.org/abs/1610.09893](https://arxiv.org/abs/1610.09893)

##### PDF
[https://arxiv.org/pdf/1610.09893](https://arxiv.org/pdf/1610.09893)

