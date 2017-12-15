---
layout: post
title: "Label-Dependencies Aware Recurrent Neural Networks"
date: 2017-06-06 13:10:49
categories: arXiv_CL
tags: arXiv_CL Embedding RNN
author: Yoann Dupont, Marco Dinarelli, Isabelle Tellier
mathjax: true
---

* content
{:toc}

##### Abstract
In the last few years, Recurrent Neural Networks (RNNs) have proved effective on several NLP tasks. Despite such great success, their ability to model \emph{sequence labeling} is still limited. This lead research toward solutions where RNNs are combined with models which already proved effective in this domain, such as CRFs. In this work we propose a solution far simpler but very effective: an evolution of the simple Jordan RNN, where labels are re-injected as input into the network, and converted into embeddings, in the same way as words. We compare this RNN variant to all the other RNN models, Elman and Jordan RNN, LSTM and GRU, on two well-known tasks of Spoken Language Understanding (SLU). Thanks to label embeddings and their combination at the hidden layer, the proposed variant, which uses more parameters than Elman and Jordan RNNs, but far fewer than LSTM and GRU, is more effective than other RNNs, but also outperforms sophisticated CRF models.

##### Abstract (translated by Google)
在过去的几年里，循环神经网络（RNN）在几个NLP任务中被证明是有效的。尽管取得如此巨大的成功，但它们对“序列标签”进行建模的能力仍然有限。这个领先的研究方向是将RNN与已经在这个领域证明有效的模型（如CRF）结合起来。在这项工作中，我们提出了一个简单但非常有效的解决方案：简单的Jordan RNN的演变，标签被重新注入到网络中，并被转换成嵌入，就像文字一样。我们将这个RNN变体与所有其他RNN模型（Elman和Jordan RNN，LSTM和GRU）在口语能力理解（SLU）这两个众所周知的任务上进行了比较。由于标签嵌入及其隐含层的组合，所提出的使用比Elman和Jordan RNN更多的参数，但比LSTM和GRU少得多的参数比其他RNN更有效，但也优于复杂的CRF模型。

##### URL
[https://arxiv.org/abs/1706.01740](https://arxiv.org/abs/1706.01740)

##### PDF
[https://arxiv.org/pdf/1706.01740](https://arxiv.org/pdf/1706.01740)

