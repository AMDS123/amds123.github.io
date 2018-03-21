---
layout: post
title: "Controlling Decoding for More Abstractive Summaries with Copy-Based Networks"
date: 2018-03-20 03:32:35
categories: arXiv_CL
tags: arXiv_CL Attention Summarization
author: Noah Weber, Leena Shekhar, Niranjan Balasubramanian, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based neural abstractive summarization systems equipped with copy mechanisms have shown promising results. Despite this success, it has been noticed that such a system generates a summary by mostly, if not entirely, copying over phrases, sentences, and sometimes multiple consecutive sentences from an input paragraph, effectively performing extractive summarization. In this paper, we verify this behavior using the latest neural abstractive summarization system - a pointer-generator network. We propose a simple baseline method that allows us to control the amount of copying without retraining. Experiments indicate that the method provides a strong baseline for abstractive systems looking to obtain high ROUGE scores while minimizing overlap with the source article, substantially reducing the n-gram overlap with the original article while keeping within 2 points of the original model's ROUGE score.

##### Abstract (translated by Google)
配备复制机制的基于注意力的神经抽象概括系统已经显示出有希望的结果。尽管取得了这样的成功，但已经注意到，这样的系统大多数（如果不是全部的话）复制短语，句子，并且有时从输入段落复制连续的多个句子，从而有效地执行提取摘要。在本文中，我们使用最新的神经抽象汇总系统 - 指针生成器网络来验证此行为。我们提出了一个简单的基准方法，可以让我们无需再培训即可控制复印量。实验表明，该方法为抽象系统提供了一个强大的基线，以期获得高ROUGE分数，同时最大限度地减少与源文章的重叠，大大减少了与原始文章的n-gram重叠，同时保持在原始模型的ROUGE评分的2分之内。

##### URL
[http://arxiv.org/abs/1803.07038](http://arxiv.org/abs/1803.07038)

##### PDF
[http://arxiv.org/pdf/1803.07038](http://arxiv.org/pdf/1803.07038)

