---
layout: post
title: "The Importance of Generation Order in Language Modeling"
date: 2018-08-23 19:17:24
categories: arXiv_CL
tags: arXiv_CL Summarization Language_Model
author: Nicolas Ford, Daniel Duckworth, Mohammad Norouzi, George E. Dahl
mathjax: true
---

* content
{:toc}

##### Abstract
Neural language models are a critical component of state-of-the-art systems for machine translation, summarization, audio transcription, and other tasks. These language models are almost universally autoregressive in nature, generating sentences one token at a time from left to right. This paper studies the influence of token generation order on model quality via a novel two-pass language model that produces partially-filled sentence "templates" and then fills in missing tokens. We compare various strategies for structuring these two passes and observe a surprisingly large variation in model quality. We find the most effective strategy generates function words in the first pass followed by content words in the second. We believe these experimental results justify a more extensive investigation of generation order for neural language models.

##### Abstract (translated by Google)
神经语言模型是机器翻译，摘要，音频转录和其他任务的最先进系统的关键组成部分。这些语言模型本质上几乎普遍具有自回归性，从左到右一次产生一个句法。本文通过一种新的双通语言模型研究了令牌生成顺序对模型质量的影响，该模型产生了部分填充的句子“模板”，然后填写了缺失的令牌。我们比较了构建这两个通道的各种策略，并观察到模型质量的惊人大变化。我们发现最有效的策略在第一遍中生成功能词，然后在第二遍中生成内容词。我们相信这些实验结果证明了对神经语言模型的生成顺序进行更广泛的研究是正确的。

##### URL
[http://arxiv.org/abs/1808.07910](http://arxiv.org/abs/1808.07910)

##### PDF
[http://arxiv.org/pdf/1808.07910](http://arxiv.org/pdf/1808.07910)

