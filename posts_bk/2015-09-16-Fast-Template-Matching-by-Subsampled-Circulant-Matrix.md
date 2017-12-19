---
layout: post
title: "Fast Template Matching by Subsampled Circulant Matrix"
date: 2015-09-16 09:38:29
categories: arXiv_CV
tags: arXiv_CV Relation
author: Sung-Hsien Hsieh, Chun-Shien Lu, and Soo-Chang Pei
mathjax: true
---

* content
{:toc}

##### Abstract
Template matching is widely used for many applications in image and signal processing and usually is time-critical. Traditional methods usually focus on how to reduce the search locations by coarse-to-fine strategy or full search combined with pruning strategy. However, the computation cost of those methods is easily dominated by the size of signal N instead of that of template K. This paper proposes a probabilistic and fast matching scheme, which computation costs requires O(N) additions and O(K \log K) multiplications, based on cross-correlation. The nuclear idea is to first downsample signal, which size becomes O(K), and then subsequent operations only involves downsampled signals. The probability of successful match depends on cross-correlation between signal and the template. We show the sufficient condition for successful match and prove that the probability is high for binary signals with K^2/log K >= O(N). The experiments shows this proposed scheme is fast and efficient and supports the theoretical results.

##### Abstract (translated by Google)
模板匹配广泛用于图像和信号处理中的许多应用，并且通常是时间关键的。传统方法通常关注如何通过粗到精的策略或全搜索与修剪策略的结合来减少搜索位置。然而，这些方法的计算成本很容易受信号N的大小的影响，而不是模板K的大小。本文提出了一种概率快速匹配方案，其计算成本要求O（N）加法和O（K \ log K ）乘法，基于互相关。核的想法是首先对信号进行降采样，其大小变为O（K），然后后续操作只涉及降采样信号。成功匹配的概率取决于信号和模板之间的互相关。我们给出了匹配成功的充分条件，证明了K ^ 2 / log K> = O（N）的二进制信号的概率很高。实验结果表明，该方案快速有效，支持理论结果。

##### URL
[https://arxiv.org/abs/1509.04863](https://arxiv.org/abs/1509.04863)

##### PDF
[https://arxiv.org/pdf/1509.04863](https://arxiv.org/pdf/1509.04863)

