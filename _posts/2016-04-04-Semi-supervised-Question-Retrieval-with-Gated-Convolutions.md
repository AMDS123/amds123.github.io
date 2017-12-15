---
layout: post
title: "Semi-supervised Question Retrieval with Gated Convolutions"
date: 2016-04-04 00:29:15
categories: arXiv_CL
tags: arXiv_CL CNN RNN
author: Tao Lei, Hrishikesh Joshi, Regina Barzilay, Tommi Jaakkola, Katerina Tymoshenko, Alessandro Moschitti, Lluis Marquez
mathjax: true
---

* content
{:toc}

##### Abstract
Question answering forums are rapidly growing in size with no effective automated ability to refer to and reuse answers already available for previous posted questions. In this paper, we develop a methodology for finding semantically related questions. The task is difficult since 1) key pieces of information are often buried in extraneous details in the question body and 2) available annotations on similar questions are scarce and fragmented. We design a recurrent and convolutional model (gated convolution) to effectively map questions to their semantic representations. The models are pre-trained within an encoder-decoder framework (from body to title) on the basis of the entire raw corpus, and fine-tuned discriminatively from limited annotations. Our evaluation demonstrates that our model yields substantial gains over a standard IR baseline and various neural network architectures (including CNNs, LSTMs and GRUs).

##### Abstract (translated by Google)
问题回答论坛的规模迅速增长，没有有效的自动化能力来引用和重复以前发布的问题已有的答案。在本文中，我们制定了一个寻找语义相关问题的方法。这个任务是困难的，因为1）关键信息通常被埋在问题主体的无关细节中，2）类似问题上的可用注释是稀缺和分散的。我们设计一个循环卷积模型（门控卷积）来有效地将问题映射到它们的语义表示。在整个原始语料库的基础上，在编码器 - 译码器框架（从主体到标题）中对模型进行预先训练，并且从有限的注释区分地进行微调。我们的评估表明，我们的模型比标准的IR基线和各种神经网络体系结构（包括CNN，LSTM和GRU）产生了巨大的收益。

##### URL
[https://arxiv.org/abs/1512.05726](https://arxiv.org/abs/1512.05726)

##### PDF
[https://arxiv.org/pdf/1512.05726](https://arxiv.org/pdf/1512.05726)

