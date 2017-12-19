---
layout: post
title: "Making sense of randomness: an approach for fast recovery of compressively sensed signals"
date: 2015-07-25 07:11:00
categories: arXiv_CV
tags: arXiv_CV Sparse
author: V. Abrol, P. Sharma, A. K Sao
mathjax: true
---

* content
{:toc}

##### Abstract
In compressed sensing (CS) framework, a signal is sampled below Nyquist rate, and the acquired compressed samples are generally random in nature. However, for efficient estimation of the actual signal, the sensing matrix must preserve the relative distances among the acquired compressed samples. Provided this condition is fulfilled, we show that CS samples will preserve the envelope of the actual signal even at different compression ratios. Exploiting this envelope preserving property of CS samples, we propose a new fast dictionary learning (DL) algorithm which is able to extract prototype signals from compressive samples for efficient sparse representation and recovery of signals. These prototype signals are orthogonal intrinsic mode functions (IMFs) extracted using empirical mode decomposition (EMD), which is one of the popular methods to capture the envelope of a signal. The extracted IMFs are used to build the dictionary without even comprehending the original signal or the sensing matrix. Moreover, one can build the dictionary on-line as new CS samples are available. In particularly, to recover first $L$ signals ($\in\mathbb{R}^n$) at the decoder, one can build the dictionary in just $\mathcal{O}(nL\log n)$ operations, that is far less as compared to existing approaches. The efficiency of the proposed approach is demonstrated experimentally for recovery of speech signals.

##### Abstract (translated by Google)
在压缩感知（CS）框架中，信号被采样为低于奈奎斯特速率，并且获取的压缩样本通常是随机的。然而，为了有效估计实际信号，感测矩阵必须保持所获取的压缩样本之间的相对距离。如果满足这个条件，我们显示即使在不同的压缩比下，CS样本也会保留实际信号的包络。利用CS样本的包络保持特性，提出了一种新的快速字典学习（DL）算法，能够从压缩样本中提取原型信号，实现信号的高效稀疏表示和恢复。这些原型信号是使用经验模式分解（EMD）提取的正交固有模式函数（IMF），这是捕获信号包络的常用方法之一。提取的IMFs用于构建词典，甚至不理解原始信号或感知矩阵。此外，可以在新的CS样本可用时在线建立字典。特别是，要在解码器中恢复第一个$ L $信号（$ \ in \ mathbb {R} ^ n $），可以在$ \ mathcal {O}（nL \ log n）$操作中建立字典，与现有方法相比要少得多。所提出的方法的效率通过实验证明用于恢复语音信号。

##### URL
[https://arxiv.org/abs/1507.07077](https://arxiv.org/abs/1507.07077)

##### PDF
[https://arxiv.org/pdf/1507.07077](https://arxiv.org/pdf/1507.07077)

