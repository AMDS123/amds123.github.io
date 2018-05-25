---
layout: post
title: "FastFCA-AS: Joint Diagonalization Based Acceleration of Full-Rank Spatial Covariance Analysis for Separating Any Number of Sources"
date: 2018-05-24 03:46:20
categories: arXiv_SD
tags: arXiv_SD
author: Nobutaka Ito, Tomohiro Nakatani
mathjax: true
---

* content
{:toc}

##### Abstract
Here we propose FastFCA-AS, an accelerated algorithm for Full-rank spatial Covariance Analysis (FCA), which is a robust audio source separation method proposed by Duong et al. ["Under-determined reverberant audio source separation using a full-rank spatial covariance model," IEEE Trans. ASLP, vol. 18, no. 7, pp. 1830-1840, Sept. 2010]. In the conventional FCA, matrix inversion and matrix multiplication are required at each time-frequency point in each iteration of an iterative parameter estimation algorithm. This causes a heavy computational load, thereby rendering the FCA infeasible in many applications. To overcome this drawback, we take a joint diagonalization approach, whereby matrix inversion and matrix multiplication are reduced to mere inversion and multiplication of diagonal entries. This makes the FastFCA-AS significantly faster than the FCA and even applicable to observed data of long duration or a situation with restricted computational resources. Although we have already proposed another acceleration of the FCA for two sources, the proposed FastFCA-AS is applicable to an arbitrary number of sources. In an experiment with three sources and three microphones, the FastFCA-AS was over 420 times faster than the FCA with a slightly better source separation performance.

##### Abstract (translated by Google)
在这里，我们提出FastFCA-AS，一种用于Full-rank空间协方差分析（FCA）的加速算法，该算法是由Duong等人提出的强健的音频源分离方法。 [“使用全秩空间协方差模型的欠定混响音频源分离”，IEEE Trans。 ASLP，vol。 18，没有。 7，第1830-1840页，2010年9月]。在传统的FCA中，在迭代参数估计算法的每次迭代中，在每个时频点需要矩阵求逆和矩阵乘法。这会导致沉重的计算负担，从而导致FCA在许多应用中不可行。为了克服这个缺点，我们采用联合对角化方法，其中矩阵求逆和矩阵乘法被减少为仅仅对角条目的反转和乘法。这使得FastFCA-AS比FCA快得多，甚至适用于长时间观测数据或计算资源有限的情况。虽然我们已经提出了两种来源的FCA的另一个加速，但是所提出的FastFCA-AS适用于任意数量的来源。在三个信号源和三个麦克风的实验中，FastFCA-AS比FCA的速度快420多倍，并具有更好的信号源分离性能。

##### URL
[http://arxiv.org/abs/1805.09498](http://arxiv.org/abs/1805.09498)

##### PDF
[http://arxiv.org/pdf/1805.09498](http://arxiv.org/pdf/1805.09498)

