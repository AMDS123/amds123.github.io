---
layout: post
title: "Get To The Point: Summarization with Pointer-Generator Networks"
date: 2017-04-25 05:47:50
categories: arXiv_CL
tags: arXiv_CL Attention Summarization
author: Abigail See, Peter J. Liu, Christopher D. Manning
mathjax: true
---

* content
{:toc}

##### Abstract
Neural sequence-to-sequence models have provided a viable new approach for abstractive text summarization (meaning they are not restricted to simply selecting and rearranging passages from the original text). However, these models have two shortcomings: they are liable to reproduce factual details inaccurately, and they tend to repeat themselves. In this work we propose a novel architecture that augments the standard sequence-to-sequence attentional model in two orthogonal ways. First, we use a hybrid pointer-generator network that can copy words from the source text via pointing, which aids accurate reproduction of information, while retaining the ability to produce novel words through the generator. Second, we use coverage to keep track of what has been summarized, which discourages repetition. We apply our model to the CNN / Daily Mail summarization task, outperforming the current abstractive state-of-the-art by at least 2 ROUGE points.

##### Abstract (translated by Google)
神经序列到序列模型为抽象文本摘要提供了一种可行的新方法（意思是它们不限于简单地从原始文本中选择和重新排列段落）。然而，这些模式有两个缺点：他们很容易重现事实的细节不准确，往往会重复自己。在这项工作中，我们提出了一种新颖的架构，以两种正交的方式来增强标准的序列到序列的注意力模型。首先，我们使用一个混合的指针生成器网络，它可以通过指向从源文本中复制单词，这有助于信息的准确再现，同时保留通过生成器生成新单词的能力。其次，我们使用覆盖范围来追踪所总结的内容，这不利于重复。我们将模型应用到CNN /每日邮件摘要任务中，至少有2个ROUGE要点胜过目前的抽象技术水平。

##### URL
[https://arxiv.org/abs/1704.04368](https://arxiv.org/abs/1704.04368)

##### PDF
[https://arxiv.org/pdf/1704.04368](https://arxiv.org/pdf/1704.04368)

