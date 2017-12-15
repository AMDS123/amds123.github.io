---
layout: post
title: "Recurrent Additive Networks"
date: 2017-06-29 14:37:32
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Kenton Lee, Omer Levy, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce recurrent additive networks (RANs), a new gated RNN which is distinguished by the use of purely additive latent state updates. At every time step, the new state is computed as a gated component-wise sum of the input and the previous state, without any of the non-linearities commonly used in RNN transition dynamics. We formally show that RAN states are weighted sums of the input vectors, and that the gates only contribute to computing the weights of these sums. Despite this relatively simple functional form, experiments demonstrate that RANs perform on par with LSTMs on benchmark language modeling problems. This result shows that many of the non-linear computations in LSTMs and related networks are not essential, at least for the problems we consider, and suggests that the gates are doing more of the computational work than previously understood.

##### Abstract (translated by Google)
我们引入了循环加法网络（RANs），一种新的门控RNN，其特征在于使用纯粹的加性潜态更新。在每个时间步，新的状态被计算为输入和前一状态的门控分量和，没有RNN转换动态中常用的任何非线性。我们正式地表明，RAN状态是输入向量的加权和，并且门只有助于计算这些和的权重。尽管这个相对简单的功能形式，实验证明RAN在基准语言建模问题上与LSTM相媲美。这个结果表明，在LSTM和相关网络中的许多非线性计算并不是至关重要的，至少对于我们所考虑的问题来说，并且表明这些门正在做比以前更多的计算工作。

##### URL
[https://arxiv.org/abs/1705.07393](https://arxiv.org/abs/1705.07393)

##### PDF
[https://arxiv.org/pdf/1705.07393](https://arxiv.org/pdf/1705.07393)

