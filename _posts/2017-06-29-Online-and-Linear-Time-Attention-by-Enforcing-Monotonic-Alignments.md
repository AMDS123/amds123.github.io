---
layout: post
title: "Online and Linear-Time Attention by Enforcing Monotonic Alignments"
date: 2017-06-29 21:14:58
categories: arXiv_CL
tags: arXiv_CL Attention Summarization Speech_Recognition Recognition
author: Colin Raffel, Minh-Thang Luong, Peter J. Liu, Ron J. Weiss, Douglas Eck
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural network models with an attention mechanism have proven to be extremely effective on a wide variety of sequence-to-sequence problems. However, the fact that soft attention mechanisms perform a pass over the entire input sequence when producing each element in the output sequence precludes their use in online settings and results in a quadratic time complexity. Based on the insight that the alignment between input and output sequence elements is monotonic in many problems of interest, we propose an end-to-end differentiable method for learning monotonic alignments which, at test time, enables computing attention online and in linear time. We validate our approach on sentence summarization, machine translation, and online speech recognition problems and achieve results competitive with existing sequence-to-sequence models.

##### Abstract (translated by Google)
具有关注机制的递归神经网络模型已被证明在各种各样的序列到序列问题上是非常有效的。然而，当在输出序列中产生每个元素时，软注意机制执行整个输入序列的事实妨碍了它们在在线设置中的使用，并导致二次时间复杂度。基于对输入和输出序列元素在许多问题中单调性的认识，我们提出了一种端到端的可微方法来学习单调对齐，在测试时间，使得在线和线性时间计算注意力。我们在句子总结，机器翻译和在线语音识别问题上验证了我们的方法，并且实现了与现有的序列 - 序列模型相竞争的结果。

##### URL
[https://arxiv.org/abs/1704.00784](https://arxiv.org/abs/1704.00784)

##### PDF
[https://arxiv.org/pdf/1704.00784](https://arxiv.org/pdf/1704.00784)

