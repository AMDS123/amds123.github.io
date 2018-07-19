---
layout: post
title: "Forward Attention in Sequence-to-sequence Acoustic Modelling for Speech Synthesis"
date: 2018-07-18 01:59:26
categories: arXiv_CL
tags: arXiv_CL Attention
author: Jing-Xuan Zhang, Zhen-Hua Ling, Li-Rong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a forward attention method for the sequenceto- sequence acoustic modeling of speech synthesis. This method is motivated by the nature of the monotonic alignment from phone sequences to acoustic sequences. Only the alignment paths that satisfy the monotonic condition are taken into consideration at each decoder timestep. The modified attention probabilities at each timestep are computed recursively using a forward algorithm. A transition agent for forward attention is further proposed, which helps the attention mechanism to make decisions whether to move forward or stay at each decoder timestep. Experimental results show that the proposed forward attention method achieves faster convergence speed and higher stability than the baseline attention method. Besides, the method of forward attention with transition agent can also help improve the naturalness of synthetic speech and control the speed of synthetic speech effectively.

##### Abstract (translated by Google)
本文提出了一种前向注意方法，用于语音合成的序列序列声学建模。该方法的动机是从电话序列到声音序列的单调对齐的性质。在每个解码器时间步长仅考虑满足单调条件的对准路径。使用前向算法递归地计算每个时间步的修改的注意概率。进一步提出了一种用于前向关注的转移代理，其有助于关注机制做出是继续前进还是停留在每个解码器时间步长的决定。实验结果表明，与基线注意方法相比，所提出的前向注意方法具有更快的收敛速度和更高的稳定性。此外，转移因子向前注意的方法也有助于提高合成语音的自然度，有效地控制合成语音的速度。

##### URL
[https://arxiv.org/abs/1807.06736](https://arxiv.org/abs/1807.06736)

##### PDF
[https://arxiv.org/pdf/1807.06736](https://arxiv.org/pdf/1807.06736)

