---
layout: post
title: "Unsupervised Abstractive Sentence Summarization using Length Controlled Variational Autoencoder"
date: 2018-09-14 02:52:02
categories: arXiv_CL
tags: arXiv_CL Summarization Inference
author: Raphael Schumann
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a unsupervised approach to summarize sentences in an abstractive way using Variational Autoencoder (VAE). VAE are known to learn a semantically rich latent variable, representing the a high dimensional input. VAEs are trained by learning to reconstruct the input from the probabilistic latent variable. Explicitly providing the information about output length during training influences the VAE to not encode this information and thus can be manipulated during inference. Instructing the decoder to produce a shorter output sequence leads to expressing the input sentence with fewer words. We show on different summarization data sets, that these shorter sentences can not beat a simple baseline but yield higher ROUGE scores than trying to reconstruct the whole sentence.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种无监督的方法，使用变分自动编码器（VAE）以抽象的方式汇总句子。已知VAE学习语义丰富的潜变量，表示高维输入。通过学习重建来自概率潜变量的输入来训练VAE。在训练期间明确地提供关于输出长度的信息影响VAE不对该信息进行编码，因此可以在推理期间操纵。指示解码器产生较短的输出序列导致用较少的单词表达输入句子。我们在不同的摘要数据集上显示，这些较短的句子不能超过简单的基线，但产生的ROUGE得分高于尝试重建整个句子。

##### URL
[http://arxiv.org/abs/1809.05233](http://arxiv.org/abs/1809.05233)

##### PDF
[http://arxiv.org/pdf/1809.05233](http://arxiv.org/pdf/1809.05233)

