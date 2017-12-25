---
layout: post
title: "Slim Embedding Layers for Recurrent Neural Language Models"
date: 2017-12-22 02:26:09
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Zhongliang Li, Raymond Kulhanek, Shaojun Wang, Yunxin Zhao, Shuang Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural language models are the state-of-the-art models for language modeling. When the vocabulary size is large, the space taken to store the model parameters becomes the bottleneck for the use of recurrent neural language models. In this paper, we introduce a simple space compression method that randomly shares the structured parameters at both the input and output embedding layers of the recurrent neural language models to significantly reduce the size of model parameters, but still compactly represent the original input and output embedding layers. The method is easy to implement and tune. Experiments on several data sets show that the new method can get similar perplexity and BLEU score results while only using a very tiny fraction of parameters.

##### Abstract (translated by Google)
递归神经语言模型是语言建模的最新模型。当词汇量大时，存储模型参数所需的空间就成为循环神经语言模型使用的瓶颈。在本文中，我们引入一种简单的空间压缩方法，在递归神经语言模型的输入和输出嵌入层上随机共享结构化参数，以显着减小模型参数的大小，但仍然紧凑地表示原始输入和输出嵌入层。该方法易于实现和调整。对几个数据集的实验表明，新方法可以得到类似的困惑和BLEU得分结果，而只使用很小的一部分参数。

##### URL
[http://arxiv.org/abs/1711.09873](http://arxiv.org/abs/1711.09873)

##### PDF
[http://arxiv.org/pdf/1711.09873](http://arxiv.org/pdf/1711.09873)

