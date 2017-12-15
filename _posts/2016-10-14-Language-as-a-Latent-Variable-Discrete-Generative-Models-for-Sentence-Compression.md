---
layout: post
title: "Language as a Latent Variable: Discrete Generative Models for Sentence Compression"
date: 2016-10-14 00:21:00
categories: arXiv_CL
tags: arXiv_CL Inference Language_Model
author: Yishu Miao, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we explore deep generative models of text in which the latent representation of a document is itself drawn from a discrete language model distribution. We formulate a variational auto-encoder for inference in this model and apply it to the task of compressing sentences. In this application the generative model first draws a latent summary sentence from a background language model, and then subsequently draws the observed sentence conditioned on this latent summary. In our empirical evaluation we show that generative formulations of both abstractive and extractive compression yield state-of-the-art results when trained on a large amount of supervised data. Further, we explore semi-supervised compression scenarios where we show that it is possible to achieve performance competitive with previously proposed supervised models while training on a fraction of the supervised data.

##### Abstract (translated by Google)
在这项工作中，我们探索文本的深层生成模型，其中文档的潜在表示本身是从离散语言模型分布中绘制的。在这个模型中我们制定了一个推理变分自动编码器，并将其用于压缩句子的任务。在这个应用中，生成模型首先从一个背景语言模型中提取一个潜在的总结句子，然后在这个潜在的总结上绘制观察到的句子。在我们的实证评估中，我们表明，在大量监督数据的训练下，抽象压缩和抽取压缩的生成公式都会产生最新的结果。此外，我们探索半监督的压缩情景，其中我们表明，有可能实现与先前提出的监督模型的性能竞争，同时对监督数据的一小部分进行训练。

##### URL
[https://arxiv.org/abs/1609.07317](https://arxiv.org/abs/1609.07317)

##### PDF
[https://arxiv.org/pdf/1609.07317](https://arxiv.org/pdf/1609.07317)

