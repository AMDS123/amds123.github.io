---
layout: post
title: "Hierarchical Memory Networks for Answer Selection on Unknown Words"
date: 2016-09-28 10:03:05
categories: arXiv_CV
tags: arXiv_CV Attention Prediction Memory_Networks
author: Jiaming Xu, Jing Shi, Yiqun Yao, Suncong Zheng, Bo Xu, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, end-to-end memory networks have shown promising results on Question Answering task, which encode the past facts into an explicit memory and perform reasoning ability by making multiple computational steps on the memory. However, memory networks conduct the reasoning on sentence-level memory to output coarse semantic vectors and do not further take any attention mechanism to focus on words, which may lead to the model lose some detail information, especially when the answers are rare or unknown words. In this paper, we propose a novel Hierarchical Memory Networks, dubbed HMN. First, we encode the past facts into sentence-level memory and word-level memory respectively. Then, (k)-max pooling is exploited following reasoning module on the sentence-level memory to sample the (k) most relevant sentences to a question and feed these sentences into attention mechanism on the word-level memory to focus the words in the selected sentences. Finally, the prediction is jointly learned over the outputs of the sentence-level reasoning module and the word-level attention mechanism. The experimental results demonstrate that our approach successfully conducts answer selection on unknown words and achieves a better performance than memory networks.

##### Abstract (translated by Google)
最近，端到端存储器网络在“问题回答”任务中表现出了令人满意的结果，该任务将过去的事实编码到显式存储器中，并通过在存储器上进行多个计算步骤来执行推理能力。然而，记忆网络在句级存储器上进行推理以输出粗糙的语义向量，并且不再采取任何注意机制来关注单词，这可能导致模型丢失一些细节信息，特别是当答案很少或者未知的单词时。在本文中，我们提出了一个新的分层存储网络，被称为HMN。首先，我们将过去的事实分别编码为句级存储器和字级存储器。然后，利用句子级存储器上的推理模块对（k）-max池进行采样，将（k）个最相关的句子采样到一个问题上，并将这些句子送入字级存储器的注意机制中，选定的句子。最后，这个预测是通过句子级推理模块和单词级关注机制的输出共同获得的。实验结果表明，我们的方法成功地进行了对未知单词的回答选择，并且实现了比内存网络更好的性能。

##### URL
[https://arxiv.org/abs/1609.08843](https://arxiv.org/abs/1609.08843)

##### PDF
[https://arxiv.org/pdf/1609.08843](https://arxiv.org/pdf/1609.08843)

