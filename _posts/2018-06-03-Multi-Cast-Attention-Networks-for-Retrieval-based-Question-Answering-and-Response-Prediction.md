---
layout: post
title: "Multi-Cast Attention Networks for Retrieval-based Question Answering and Response Prediction"
date: 2018-06-03 12:22:28
categories: arXiv_AI
tags: arXiv_AI QA Attention Embedding Represenation_Learning Prediction
author: Yi Tay, Luu Anh Tuan, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
Attention is typically used to select informative sub-phrases that are used for prediction. This paper investigates the novel use of attention as a form of feature augmentation, i.e, casted attention. We propose Multi-Cast Attention Networks (MCAN), a new attention mechanism and general model architecture for a potpourri of ranking tasks in the conversational modeling and question answering domains. Our approach performs a series of soft attention operations, each time casting a scalar feature upon the inner word embeddings. The key idea is to provide a real-valued hint (feature) to a subsequent encoder layer and is targeted at improving the representation learning process. There are several advantages to this design, e.g., it allows an arbitrary number of attention mechanisms to be casted, allowing for multiple attention types (e.g., co-attention, intra-attention) and attention variants (e.g., alignment-pooling, max-pooling, mean-pooling) to be executed simultaneously. This not only eliminates the costly need to tune the nature of the co-attention layer, but also provides greater extents of explainability to practitioners. Via extensive experiments on four well-known benchmark datasets, we show that MCAN achieves state-of-the-art performance. On the Ubuntu Dialogue Corpus, MCAN outperforms existing state-of-the-art models by $9\%$. MCAN also achieves the best performing score to date on the well-studied TrecQA dataset.

##### Abstract (translated by Google)
注意力通常用于选择用于预测的信息性子短语。本文研究了注意力作为一种特征增强形式的新颖用途，即流行注意力。我们提出多重注意网络（MCAN），这是一种新的关注机制和一般模型体系结构，用于对话建模和问答领域中的排序任务。我们的方法执行一系列软注意操作，每次在内部词嵌入时施加标量特征。关键的想法是向后续的编码器层提供实值提示（特征），并且旨在改进表示学习过程。这种设计有几个优点，例如，它允许任意数量的关注机制被传播，允许多种关注类型（例如，共同关注，内部关注）和关注变体（例如，对齐池，最大 - 汇集，平均汇集）同时执行。这不仅消除了调整共同关注层的本质的昂贵需求，而且为从业人员提供了更大程度的可解释性。通过对四个众所周知的基准数据集进行广泛的实验，我们证明MCAN可以实现最先进的性能。在Ubuntu Dialogue语料库上，MCAN比现有的最新型号性能高出9美元/％$。 MCAN也通过充分研究的TrecQA数据集实现了迄今为止表现最好的分数。

##### URL
[http://arxiv.org/abs/1806.00778](http://arxiv.org/abs/1806.00778)

##### PDF
[http://arxiv.org/pdf/1806.00778](http://arxiv.org/pdf/1806.00778)

