---
layout: post
title: "Unsupervised Learning of Word-Sequence Representations from Scratch via Convolutional Tensor Decomposition"
date: 2017-05-04 22:32:17
categories: arXiv_CL
tags: arXiv_CL Embedding CNN Language_Model
author: Furong Huang, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised text embeddings extraction is crucial for text understanding in machine learning. Word2Vec and its variants have received substantial success in mapping words with similar syntactic or semantic meaning to vectors close to each other. However, extracting context-aware word-sequence embedding remains a challenging task. Training over large corpus is difficult as labels are difficult to get. More importantly, it is challenging for pre-trained models to obtain word-sequence embeddings that are universally good for all downstream tasks or for any new datasets. We propose a two-phased ConvDic+DeconvDec framework to solve the problem by combining a word-sequence dictionary learning model with a word-sequence embedding decode model. We propose a convolutional tensor decomposition mechanism to learn good word-sequence phrase dictionary in the learning phase. It is proved to be more accurate and much more efficient than the popular alternating minimization method. In the decode phase, we introduce a deconvolution framework that is immune to the problem of varying sentence lengths. The word-sequence embeddings we extracted using ConvDic+DeconvDec are universally good for a few downstream tasks we test on. The framework requires neither pre-training nor prior/outside information.

##### Abstract (translated by Google)
无监督文本嵌入提取对于机器学习中的文本理解是至关重要的。 Word2Vec及其变体在将具有相似句法或语义含义的单词映射到彼此接近的矢量方面已经取得了实质性的成功。然而，提取上下文感知的字序列嵌入仍然是一个具有挑战性的任务。由于标签很难获得，因此对大型语料库的培训很困难。更重要的是，对于预先训练的模型来说，获得对于所有下游任务或任何新数据集普遍好的字序列嵌入是具有挑战性的。我们提出了一个两阶段的ConvDic + DeconvDec框架来解决这个问题，把一个字序列字典学习模型和一个字序列嵌入解码模型结合起来。我们提出了一个卷积张量分解机制，在学习阶段学习好的词序短语词典。与流行的交替最小化方法相比，它被证明是更准确和更有效的。在解码阶段，我们引入了一个不受句子长度变化影响的反卷积框架。我们使用ConvDic + DeconvDec提取的字序列嵌入对于我们测试的一些下游任务来说是非常好的。该框架既不需要预培训，也不需要事先/外部信息。

##### URL
[https://arxiv.org/abs/1606.03153](https://arxiv.org/abs/1606.03153)

##### PDF
[https://arxiv.org/pdf/1606.03153](https://arxiv.org/pdf/1606.03153)

