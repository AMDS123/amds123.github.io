---
layout: post
title: "Combining a Context Aware Neural Network with a Denoising Autoencoder for Measuring String Similarities"
date: 2018-07-16 12:29:23
categories: arXiv_CL
tags: arXiv_CL
author: Mehdi Ben Lazreg, Morten Goodwin
mathjax: true
---

* content
{:toc}

##### Abstract
Measuring similarities between strings is central for many established and fast growing research areas including information retrieval, biology, and natural language processing. The traditional approach for string similarity measurements is to define a metric over a word space that quantifies and sums up the differences between characters in two strings. The state-of-the-art in the area has, surprisingly, not evolved much during the last few decades. The majority of the metrics are based on a simple comparison between character and character distributions without consideration for the context of the words. This paper proposes a string metric that encompasses similarities between strings based on (1) the character similarities between the words including. Non-Standard and standard spellings of the same words, and (2) the context of the words. Our proposal is a neural network composed of a denoising autoencoder and what we call a context encoder specifically designed to find similarities between the words based on their context. The experimental results show that the resulting metrics succeeds in 85.4\% of the cases in finding the correct version of a non-standard spelling among the closest words, compared to 63.2\% with the established Normalised-Levenshtein distance. Besides, we show that words used in similar context are with our approach calculated to be similar than words with different contexts, which is a desirable property missing in established string metrics.

##### Abstract (translated by Google)
衡量字符串之间的相似性是许多已建立和快速发展的研究领域的核心，包括信息检索，生物学和自然语言处理。用于字符串相似性测量的传统方法是在字空间上定义度量，其量化并总结两个字符串中的字符之间的差异。令人惊讶的是，该地区最先进的技术在过去几十年中并未发生太大变化。大多数度量基于字符和字符分布之间的简单比较，而不考虑单词的上下文。本文提出了一个字符串度量，它包含了基于（1）单词之间的字符相似性的字符串之间的相似性。相同单词的非标准和标准拼写，以及（2）单词的上下文。我们的提议是一个神经网络，由一个去噪自动编码器和我们称之为上下文编码器组成的内容编码器，专门用于根据上下文查找单词之间的相似性。实验结果表明，在最接近的单词中找到非标准拼写的正确版本时，得到的度量标准成功率为85.4％，而已建立的Normalized-Levenshtein距离为63.2％。此外，我们表明在类似的上下文中使用的单词与我们的方法计算得比具有不同上下文的单词相似，这是已建立的字符串度量中缺少的理想属性。

##### URL
[http://arxiv.org/abs/1807.06414](http://arxiv.org/abs/1807.06414)

##### PDF
[http://arxiv.org/pdf/1807.06414](http://arxiv.org/pdf/1807.06414)

