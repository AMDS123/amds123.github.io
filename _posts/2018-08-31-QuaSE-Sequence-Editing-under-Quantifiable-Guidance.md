---
layout: post
title: "QuaSE: Sequence Editing under Quantifiable Guidance"
date: 2018-08-31 08:34:42
categories: arXiv_CL
tags: arXiv_CL Review
author: Yi Liao, Lidong Bing, Piji Li, Shuming Shi, Wai Lam, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the task of Quantifiable Sequence Editing (QuaSE): editing an input sequence to generate an output sequence that satisfies a given numerical outcome value measuring a certain property of the sequence, with the requirement of keeping the main content of the input sequence. For example, an input sequence could be a word sequence, such as review sentence and advertisement text. For a review sentence, the outcome could be the review rating; for an advertisement, the outcome could be the click-through rate. The major challenge in performing QuaSE is how to perceive the outcome-related wordings, and only edit them to change the outcome. In this paper, the proposed framework contains two latent factors, namely, outcome factor and content factor, disentangled from the input sentence to allow convenient editing to change the outcome and keep the content. Our framework explores the pseudo-parallel sentences by modeling their content similarity and outcome differences to enable a better disentanglement of the latent factors, which allows generating an output to better satisfy the desired outcome and keep the content. The dual reconstruction structure further enhances the capability of generating expected output by exploiting the couplings of latent factors of pseudo-parallel sentences. For evaluation, we prepared a dataset of Yelp review sentences with the ratings as outcome. Extensive experimental results are reported and discussed to elaborate the peculiarities of our framework.

##### Abstract (translated by Google)
我们提出了可量化序列编辑（QuaSE）的任务：编辑输入序列以生成满足测量序列的某个特性的给定数值结果值的输出序列，同时要求保持输入序列的主要内容。例如，输入序列可以是单词序列，例如复习句和广告文本。对于复审判决，结果可以是审查评级;对于广告，结果可以是点击率。执行QuaSE的主要挑战是如何感知与结果相关的措辞，并仅编辑它们以改变结果。在本文中，所提出的框架包含两个潜在因素，即结果因子和内容因子，从输入句中解开，以便于编辑以改变结果并保留内容。我们的框架通过对其内容相似性和结果差异进行建模来探索伪平行句子，以便更好地解开潜在因素，从而允许生成输出以更好地满足期望的结果并保持内容。双重构结构通过利用伪平行句的潜在因子的耦合，进一步增强了产生预期输出的能力。为了评估，我们准备了Yelp评论句子的数据集，其评级为结果。报告和讨论了广泛的实验结果，以阐述我们框架的特点。

##### URL
[http://arxiv.org/abs/1804.07007](http://arxiv.org/abs/1804.07007)

##### PDF
[http://arxiv.org/pdf/1804.07007](http://arxiv.org/pdf/1804.07007)

