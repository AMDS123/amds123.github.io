---
layout: post
title: "Iterative Refinement for Machine Translation"
date: 2016-10-26 16:23:30
categories: arXiv_CL
tags: arXiv_CL Attention CNN
author: Roman Novak, Michael Auli, David Grangier
mathjax: true
---

* content
{:toc}

##### Abstract
Existing machine translation decoding algorithms generate translations in a strictly monotonic fashion and never revisit previous decisions. As a result, earlier mistakes cannot be corrected at a later stage. In this paper, we present a translation scheme that starts from an initial guess and then makes iterative improvements that may revisit previous decisions. We parameterize our model as a convolutional neural network that predicts discrete substitutions to an existing translation based on an attention mechanism over both the source sentence as well as the current translation output. By making less than one modification per sentence, we improve the output of a phrase-based translation system by up to 0.4 BLEU on WMT15 German-English translation.

##### Abstract (translated by Google)
现有的机器翻译解码算法以严格单调的方式生成翻译，并且从不重复以前的决定。结果，以后的错误不可能在后期得到纠正。在本文中，我们提出了一个翻译方案，从最初的猜测开始，然后进行迭代改进，可能会重新审视以前的决定。我们将我们的模型参数化为一个卷积神经网络，根据对源句子和当前翻译输出的注意机制，预测离散替代到现有翻译。通过对每个句子进行少于一次的修改，我们在WMT15德语 - 英语翻译上将基于短语的翻译系统的输出提高了0.4 BLEU。

##### URL
[https://arxiv.org/abs/1610.06602](https://arxiv.org/abs/1610.06602)

##### PDF
[https://arxiv.org/pdf/1610.06602](https://arxiv.org/pdf/1610.06602)

