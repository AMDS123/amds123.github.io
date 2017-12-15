---
layout: post
title: "Vocabulary Selection Strategies for Neural Machine Translation"
date: 2016-10-01 02:23:03
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Gurvan L'Hostis, David Grangier, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
Classical translation models constrain the space of possible outputs by selecting a subset of translation rules based on the input sentence. Recent work on improving the efficiency of neural translation models adopted a similar strategy by restricting the output vocabulary to a subset of likely candidates given the source. In this paper we experiment with context and embedding-based selection methods and extend previous work by examining speed and accuracy trade-offs in more detail. We show that decoding time on CPUs can be reduced by up to 90% and training time by 25% on the WMT15 English-German and WMT16 English-Romanian tasks at the same or only negligible change in accuracy. This brings the time to decode with a state of the art neural translation system to just over 140 msec per sentence on a single CPU core for English-German.

##### Abstract (translated by Google)
经典翻译模型通过基于输入句子选择翻译规则的一个子集来约束可能输出的空间。近期有关提高神经翻译模型效率的工作采取了类似的策略，即将输出词汇量限制在可能的候选人子集中。在本文中，我们通过上下文和基于嵌入的选择方法进行实验，并通过更加详细地检查速度和准确性权衡来扩展以前的工作。我们表明，对于WMT15英语 - 德语和WMT16英语 - 罗马尼亚语任务，CPU上的解码时间可以减少高达90％，训练时间减少25％，精确度相同或者可以忽略不计。这使得在英语 - 德语的单个CPU内核上使用最先进的神经翻译系统进行解码的时间超过每句140毫秒。

##### URL
[https://arxiv.org/abs/1610.00072](https://arxiv.org/abs/1610.00072)

##### PDF
[https://arxiv.org/pdf/1610.00072](https://arxiv.org/pdf/1610.00072)

