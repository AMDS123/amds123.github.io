---
layout: post
title: "Multichannel Speech Separation and Enhancement Using the Convolutive Transfer Function"
date: 2018-02-26 10:00:40
categories: arXiv_SD
tags: arXiv_SD
author: Xiaofei Li, Laurent Girin, Sharon Gannot, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of speech separation and enhancement from multichannel convolutive and noisy mixtures, \emph{assuming known mixing filters}. We propose to perform the speech separation and enhancement task in the short-time Fourier transform domain, using the convolutive transfer function (CTF) approximation. Compared to time-domain filters, CTF has much less taps, consequently it has less near-common zeros among channels and less computational complexity. The work proposes three speech-source recovery methods, namely: i) the multichannel inverse filtering method, i.e. the multiple input/output inverse theorem (MINT), is exploited in the CTF domain, and for the multi-source case, ii) a beamforming-like multichannel inverse filtering method applying single source MINT and using power minimization, which is suitable whenever the source CTFs are not all known, and iii) a constrained Lasso method, where the sources are recovered by minimizing the $\ell_1$-norm to impose their spectral sparsity, with the constraint that the $\ell_2$-norm fitting cost, between the microphone signals and the mixing model involving the unknown source signals, is less than a tolerance. The noise can be reduced by setting a tolerance onto the noise power. Experiments under various acoustic conditions are carried out to evaluate the three proposed methods. The comparison between them as well as with the baseline methods is presented.

##### Abstract (translated by Google)
本文讨论了多通道卷积和噪声混合的语音分离和增强问题，假设已知混合滤波器。我们提出使用卷积传递函数（CTF）近似来在短时傅立叶变换域中执行语音分离和增强任务。与时域滤波器相比，CTF的抽头少得多，因此它在信道中具有较少的近共同零点并且计算复杂度较低。该工作提出了三种语音源恢复方法，即：i）多通道逆滤波方法，即多输入/输出逆定理（MINT），在CTF域中被利用，并且对于多源情况，ii）a类似波束成形的多通道逆滤波方法应用单源MINT并使用功率最小化，这适用于无论何时源CTF都未知的情况，以及iii）受限Lasso方法，其中通过最小化$ \ ell_1 $ -norm将麦克风信号与涉及未知源信号的混合模型之间的$ \ ell_2 $范数拟合成本的约束强加于它们的谱稀疏性，小于容差。通过在噪声功率上设置容差可以降低噪声。在各种声学条件下进行实验以评估三种提出的方​​法。介绍了它们之间的比较以及基线方法。

##### URL
[http://arxiv.org/abs/1711.07911](http://arxiv.org/abs/1711.07911)

##### PDF
[http://arxiv.org/pdf/1711.07911](http://arxiv.org/pdf/1711.07911)

