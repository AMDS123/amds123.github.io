---
layout: post
title: "Speeding up Context-based Sentence Representation Learning with Non-autoregressive Convolutional Decoding"
date: 2018-06-01 01:05:28
categories: arXiv_CL
tags: arXiv_CL CNN Represenation_Learning RNN
author: Shuai Tang, Hailin Jin, Chen Fang, Zhaowen Wang, Virginia R. de Sa
mathjax: true
---

* content
{:toc}

##### Abstract
Context plays an important role in human language understanding, thus it may also be useful for machines learning vector representations of language. In this paper, we explore an asymmetric encoder-decoder structure for unsupervised context-based sentence representation learning. We carefully designed experiments to show that neither an autoregressive decoder nor an RNN decoder is required. After that, we designed a model which still keeps an RNN as the encoder, while using a non-autoregressive convolutional decoder. We further combine a suite of effective designs to significantly improve model efficiency while also achieving better performance. Our model is trained on two different large unlabelled corpora, and in both cases the transferability is evaluated on a set of downstream NLP tasks. We empirically show that our model is simple and fast while producing rich sentence representations that excel in downstream tasks.

##### Abstract (translated by Google)
语境在人类语言理解中起着重要作用，因此它也可能对机器学习语言的向量表示有用。在本文中，我们探讨了一种用于无监督的基于上下文的句子表示学习的非对称编码器 - 解码器结构。我们精心设计的实验表明，既不需要自回归解码器也不需要RNN解码器。之后，我们设计了一个仍使用RNN作为编码器的模型，同时使用了非自回归卷积解码器。我们进一步结合了一套有效的设计来显着提高模型效率，同时实现更好的性能。我们的模型是在两个不同的大型未标记语料库上进行训练的，在这两种情况下，可转移性都是在一组下游NLP任务上进行评估的。我们凭经验证明，我们的模型简单快捷，同时产生丰富的句子表示，在下游任务中表现突出。

##### URL
[http://arxiv.org/abs/1710.10380](http://arxiv.org/abs/1710.10380)

##### PDF
[http://arxiv.org/pdf/1710.10380](http://arxiv.org/pdf/1710.10380)

