---
layout: post
title: "On the Practical Computational Power of Finite Precision RNNs for Language Recognition"
date: 2018-05-13 16:28:32
categories: arXiv_CL
tags: arXiv_CL RNN Recognition
author: Gail Weiss, Yoav Goldberg, Eran Yahav
mathjax: true
---

* content
{:toc}

##### Abstract
While Recurrent Neural Networks (RNNs) are famously known to be Turing complete, this relies on infinite precision in the states and unbounded computation time. We consider the case of RNNs with finite precision whose computation time is linear in the input length. Under these limitations, we show that different RNN variants have different computational power. In particular, we show that the LSTM and the Elman-RNN with ReLU activation are strictly stronger than the RNN with a squashing activation and the GRU. This is achieved because LSTMs and ReLU-RNNs can easily implement counting behavior. We show empirically that the LSTM does indeed learn to effectively use the counting mechanism.

##### Abstract (translated by Google)
虽然循环神经网络（RNN）被称为图灵完备，但这依赖于状态的无限精度和无限的计算时间。我们考虑具有有限精度的RNN的情况，其计算时间在输入长度上是线性的。在这些限制下，我们显示不同的RNN变体具有不同的计算能力。特别是，我们发现LSTM和具有ReLU激活的Elman-RNN严格强于压缩激活和GRU的RNN。这是因为LSTM和ReLU-RNN可以轻松实现计数行为。我们凭经验证明，LSTM确实学会有效地使用计数机制。

##### URL
[https://arxiv.org/abs/1805.04908](https://arxiv.org/abs/1805.04908)

##### PDF
[https://arxiv.org/pdf/1805.04908](https://arxiv.org/pdf/1805.04908)

