---
layout: post
title: "Bottom-Up Abstractive Summarization"
date: 2018-08-31 14:55:52
categories: arXiv_AI
tags: arXiv_AI Attention Summarization
author: Sebastian Gehrmann, Yuntian Deng, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network-based methods for abstractive summarization produce outputs that are more fluent than other techniques, but which can be poor at content selection. This work proposes a simple technique for addressing this issue: use a data-efficient content selector to over-determine phrases in a source document that should be part of the summary. We use this selector as a bottom-up attention step to constrain the model to likely phrases. We show that this approach improves the ability to compress text, while still generating fluent summaries. This two-step process is both simpler and higher performing than other end-to-end content selection models, leading to significant improvements on ROUGE for both the CNN-DM and NYT corpus. Furthermore, the content selector can be trained with as little as 1,000 sentences, making it easy to transfer a trained summarizer to a new domain.

##### Abstract (translated by Google)
基于神经网络的抽象摘要方法产生的输出比其他技术更流畅，但在内容选择方面可能较差。这项工作提出了一种解决此问题的简单技术：使用数据有效的内容选择器来过度确定源文档中应成为摘要一部分的短语。我们使用此选择器作为自下而上的关注步骤，将模型约束为可能的短语。我们表明，这种方法提高了压缩文本的能力，同时仍然生成流畅的摘要。这个两步过程比其他端到端内容选择模型更简单，性能更高，从而显着改善了CNN-DM和NYT语料库的ROUGE。此外，内容选择器可以用少至1,000个句子进行训练，从而可以轻松地将训练有素的摘要器传送到新域。

##### URL
[http://arxiv.org/abs/1808.10792](http://arxiv.org/abs/1808.10792)

##### PDF
[http://arxiv.org/pdf/1808.10792](http://arxiv.org/pdf/1808.10792)

