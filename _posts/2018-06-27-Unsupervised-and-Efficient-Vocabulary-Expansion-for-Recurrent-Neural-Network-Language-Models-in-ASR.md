---
layout: post
title: "Unsupervised and Efficient Vocabulary Expansion for Recurrent Neural Network Language Models in ASR"
date: 2018-06-27 05:50:05
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Embedding RNN Language_Model Recognition
author: Yerbolat Khassanov, Eng Siong Chng
mathjax: true
---

* content
{:toc}

##### Abstract
In automatic speech recognition (ASR) systems, recurrent neural network language models (RNNLM) are used to rescore a word lattice or N-best hypotheses list. Due to the expensive training, the RNNLM's vocabulary set accommodates only small shortlist of most frequent words. This leads to suboptimal performance if an input speech contains many out-of-shortlist (OOS) words. An effective solution is to increase the shortlist size and retrain the entire network which is highly inefficient. Therefore, we propose an efficient method to expand the shortlist set of a pretrained RNNLM without incurring expensive retraining and using additional training data. Our method exploits the structure of RNNLM which can be decoupled into three parts: input projection layer, middle layers, and output projection layer. Specifically, our method expands the word embedding matrices in projection layers and keeps the middle layers unchanged. In this approach, the functionality of the pretrained RNNLM will be correctly maintained as long as OOS words are properly modeled in two embedding spaces. We propose to model the OOS words by borrowing linguistic knowledge from appropriate in-shortlist words. Additionally, we propose to generate the list of OOS words to expand vocabulary in unsupervised manner by automatically extracting them from ASR output.

##### Abstract (translated by Google)
在自动语音识别（ASR）系统中，递归神经网络语言模型（RNNLM）被用于重新定义词格或N个最佳假设列表。由于昂贵的培训，RNNLM的词汇集只容纳最常见单词的小名单。如果一个输入语音包含许多out-of-shortlist（OOS）单词，这会导致性能不理想。一个有效的解决方案是增加候选名单的大小，并重新整个网络效率非常低。因此，我们提出了一种有效的方法来扩展预训练RNNLM的候选名单集，而不会发生昂贵的再训练和使用额外的训练数据。我们的方法利用RNNLM的结构，它可以解耦成三部分：输入投影层，中间层和输出投影层。具体来说，我们的方法扩展了嵌入矩阵的投影层，并保持中间层不变。在这种方法中，只要OOS字在两个嵌入空间中被正确地建模，预训练的RNNLM的功能将被正确地保持。我们建议通过从适当的短名单词借用语言知识来对OOS词进行建模。此外，我们建议生成OOS单词列表，以无监督的方式通过从ASR输出中自动提取词汇来扩展词汇量。

##### URL
[http://arxiv.org/abs/1806.10306](http://arxiv.org/abs/1806.10306)

##### PDF
[http://arxiv.org/pdf/1806.10306](http://arxiv.org/pdf/1806.10306)

