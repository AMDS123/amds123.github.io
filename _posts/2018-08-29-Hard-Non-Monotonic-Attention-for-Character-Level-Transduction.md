---
layout: post
title: "Hard Non-Monotonic Attention for Character-Level Transduction"
date: 2018-08-29 20:00:20
categories: arXiv_CL
tags: arXiv_CL Image_Caption Attention Caption
author: Shijie Wu, Pamela Shapiro, Ryan Cotterell
mathjax: true
---

* content
{:toc}

##### Abstract
Character-level string-to-string transduction is an important component of various NLP tasks. The goal is to map an input string to an output string, where the strings may be of different lengths and have characters taken from different alphabets. Recent approaches have used sequence-to-sequence models with an attention mechanism to learn which parts of the input string the model should focus on during the generation of the output string. Both soft attention and hard monotonic attention have been used, but hard non-monotonic attention has only been used in other sequence modeling tasks such as image captioning and has required a stochastic approximation to compute the gradient. In this work, we introduce an exact, polynomial-time algorithm for marginalizing over the exponential number of non-monotonic alignments between two strings, showing that hard attention models can be viewed as neural reparameterizations of the classical IBM Model 1. We compare soft and hard non-monotonic attention experimentally and find that the exact algorithm significantly improves performance over the stochastic approximation and outperforms soft attention.

##### Abstract (translated by Google)
字符级字符串到字符串转换是各种NLP任务的重要组成部分。目标是将输入字符串映射到输出字符串，其中字符串可以具有不同的长度并且具有来自不同字母表的字符。最近的方法使用具有注意机制的序列到序列模型来了解模型在生成输出字符串期间应该关注的输入字符串的哪些部分。已经使用了柔和注意力和硬单调注意力，但是硬非单调注意力仅用于其他序列建模任务，例如图像字幕，并且需要随机近似来计算梯度。在这项工作中，我们引入了一个精确的多项式时间算法，用于边缘化两个字符串之间的非单调对齐的指数，表明硬注意模型可以被视为经典IBM模型1的神经重新参数化。我们比较软和通过实验进行硬非单调注意，发现精确算法显着提高了随机逼近的性能，并且优于软注意。

##### URL
[http://arxiv.org/abs/1808.10024](http://arxiv.org/abs/1808.10024)

##### PDF
[http://arxiv.org/pdf/1808.10024](http://arxiv.org/pdf/1808.10024)

