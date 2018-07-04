---
layout: post
title: "Neural Random Projections for Language Modelling"
date: 2018-07-02 23:54:48
categories: arXiv_CL
tags: arXiv_CL Sparse Face Language_Model
author: Davide Nunes, Luis Antunes
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network-based language models deal with data sparsity problems by mapping the large discrete space of words into a smaller continuous space of real-valued vectors. By learning distributed vector representations for words, each training sample informs the neural network model about a combinatorial number of other patterns. We exploit the sparsity in natural language even further by encoding each unique input word using a reduced sparse random representation. In this paper, we propose an encoder for discrete inputs that uses random projections to allow for the learning of language models using significantly smaller parameter spaces when compared with similar neural network architectures. Furthermore, random projections also eliminate the dependency between a neural network architecture and the size of a pre-established dictionary. We investigate the properties of our encoding mechanism empirically, by evaluating its performance on the widely used Penn Treebank corpus, using several configurations of baseline feedforward neural network models. We show that guaranteeing approximately equidistant inner products between representations of unique discrete inputs is enough to provide the neural network model with enough information to learn useful distributed representations for these inputs. By not requiring prior enumeration of the lexicon, random projections allow us to face the dynamic and open character of natural languages.

##### Abstract (translated by Google)
基于神经网络的语言模型通过将单词的大的离散空间映射到较小的实值向量的连续空间来处理数据稀疏性问题。通过学习单词的分布式矢量表示，每个训练样本向神经网络模型通知组合数量的其他模式。我们通过使用简化的稀疏随机表示对每个唯一输入字进行编码来进一步利用自然语言中的稀疏性。在本文中，我们提出了一种离散输入编码器，它使用随机投影，与类似的神经网络架构相比，可以使用明显更小的参数空间来学习语言模型。此外，随机投影还消除了神经网络架构与预先建立的字典的大小之间的依赖性。我们通过使用基线前馈神经网络模型的几种配置评估其在广泛使用的Penn Treebank语料库中的性能，凭经验研究我们的编码机制的属性。我们表明，保证独特离散输入的表示之间近似等距的内积足以为神经网络模型提供足够的信息来学习这些输入的有用分布式表示。通过不要求事先列举词典，随机投影使我们能够面对自然语言的动态和开放性。

##### URL
[https://arxiv.org/abs/1807.00930](https://arxiv.org/abs/1807.00930)

##### PDF
[https://arxiv.org/pdf/1807.00930](https://arxiv.org/pdf/1807.00930)

