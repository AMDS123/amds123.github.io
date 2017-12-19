---
layout: post
title: "Partial Sum Minimization of Singular Values in Robust PCA: Algorithm and Applications"
date: 2015-08-13 12:51:08
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Tae-Hyun Oh, Yu-Wing Tai, Jean-Charles Bazin, Hyeongwoo Kim, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
Robust Principal Component Analysis (RPCA) via rank minimization is a powerful tool for recovering underlying low-rank structure of clean data corrupted with sparse noise/outliers. In many low-level vision problems, not only it is known that the underlying structure of clean data is low-rank, but the exact rank of clean data is also known. Yet, when applying conventional rank minimization for those problems, the objective function is formulated in a way that does not fully utilize a priori target rank information about the problems. This observation motivates us to investigate whether there is a better alternative solution when using rank minimization. In this paper, instead of minimizing the nuclear norm, we propose to minimize the partial sum of singular values, which implicitly encourages the target rank constraint. Our experimental analyses show that, when the number of samples is deficient, our approach leads to a higher success rate than conventional rank minimization, while the solutions obtained by the two approaches are almost identical when the number of samples is more than sufficient. We apply our approach to various low-level vision problems, e.g. high dynamic range imaging, motion edge detection, photometric stereo, image alignment and recovery, and show that our results outperform those obtained by the conventional nuclear norm rank minimization method.

##### Abstract (translated by Google)
通过秩最小化的鲁棒主成分分析（RPCA）是用于恢复被稀疏噪声/异常值破坏的干净数据的潜在低秩结构的有力工具。在许多低级视觉问题中，不仅知道清洁数据的底层结构是低级的，而且清洁数据的准确等级也是已知的。然而，当针对这些问题应用传统的等级最小化时，目标函数是以不能充分利用关于问题的先验目标等级信息的方式来制定的。这一观察结果激励我们调查使用秩最小化时是否有更好的替代解决方案。在本文中，我们不是最小化核范数，而是提出将奇异值的部分和最小化，这隐含地鼓励目标等级约束。我们的实验分析表明，当样本数量不足时，我们的方法导致比传统秩最小化更高的成功率，而当样本数量足够多时，两种方法得到的解决方案几乎是相同的。我们将我们的方法应用于各种低级视觉问题，例如高动态范围成像，运动边缘检测，光度立体，图像对齐和恢复，并表明我们的结果优于传统核范数秩最小化方法获得的结果。

##### URL
[https://arxiv.org/abs/1503.01444](https://arxiv.org/abs/1503.01444)

##### PDF
[https://arxiv.org/pdf/1503.01444](https://arxiv.org/pdf/1503.01444)

