---
layout: post
title: "Predefined Sparseness in Recurrent Sequence Models"
date: 2018-08-27 07:55:41
categories: arXiv_AI
tags: arXiv_AI Sparse Embedding Language_Model
author: Thomas Demeester, Johannes Deleu, Fr&#xe9;deric Godin, Chris Develder
mathjax: true
---

* content
{:toc}

##### Abstract
Inducing sparseness while training neural networks has been shown to yield models with a lower memory footprint but similar effectiveness to dense models. However, sparseness is typically induced starting from a dense model, and thus this advantage does not hold during training. We propose techniques to enforce sparseness upfront in recurrent sequence models for NLP applications, to also benefit training. First, in language modeling, we show how to increase hidden state sizes in recurrent layers without increasing the number of parameters, leading to more expressive models. Second, for sequence labeling, we show that word embeddings with predefined sparseness lead to similar performance as dense embeddings, at a fraction of the number of trainable parameters.

##### Abstract (translated by Google)
在训练神经网络时诱导稀疏性已被证明可以产生具有较低内存占用但与密集模型类似的效果的模型。然而，通常从密集模型开始引起稀疏性，因此在训练期间这种优势不成立。我们提出了在NLP应用程序的循环序列模型中预先实施稀疏性的技术，也有利于培训。首先，在语言建模中，我们展示了如何在不增加参数数量的情况下增加循环层中的隐藏状态大小，从而产生更具表现力的模型。其次，对于序列标记，我们表明具有预定义稀疏性的单词嵌入导致与密集嵌入相似的性能，只是可训练参数数量的一小部分。

##### URL
[http://arxiv.org/abs/1808.08720](http://arxiv.org/abs/1808.08720)

##### PDF
[http://arxiv.org/pdf/1808.08720](http://arxiv.org/pdf/1808.08720)

