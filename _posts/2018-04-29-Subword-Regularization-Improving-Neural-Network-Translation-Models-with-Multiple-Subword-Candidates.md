---
layout: post
title: "Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates"
date: 2018-04-29 16:13:44
categories: arXiv_CL
tags: arXiv_CL Regularization Segmentation NMT Language_Model
author: Taku Kudo
mathjax: true
---

* content
{:toc}

##### Abstract
Subword units are an effective way to alleviate the open vocabulary problems in neural machine translation (NMT). While sentences are usually converted into unique subword sequences, subword segmentation is potentially ambiguous and multiple segmentations are possible even with the same vocabulary. The question addressed in this paper is whether it is possible to harness the segmentation ambiguity as a noise to improve the robustness of NMT. We present a simple regularization method, subword regularization, which trains the model with multiple subword segmentations probabilistically sampled during training. In addition, for better subword sampling, we propose a new subword segmentation algorithm based on a unigram language model. We experiment with multiple corpora and report consistent improvements especially on low resource and out-of-domain settings.

##### Abstract (translated by Google)
子词单位是缓解神经机器翻译（NMT）中的开放词汇问题的有效方式。虽然句子通常被转换为唯一的子字词序列，但是子词分词可能是不明确的，即使使用相同的词汇，也可能有多个分词。本文讨论的问题是，是否有可能利用分割歧义作为噪声来提高NMT的鲁棒性。我们提出了一种简单的正则化方法，即子字正则化，它在训练期间训练具有概率取样的多个子字分段的模型。另外，为了更好的子字采样，我们提出了一种基于单字模型的新的子字分词算法。我们尝试使用多个语料库并报告一致的改进，特别是在资源不足和域外设置的情况下。

##### URL
[https://arxiv.org/abs/1804.10959](https://arxiv.org/abs/1804.10959)

##### PDF
[https://arxiv.org/pdf/1804.10959](https://arxiv.org/pdf/1804.10959)

