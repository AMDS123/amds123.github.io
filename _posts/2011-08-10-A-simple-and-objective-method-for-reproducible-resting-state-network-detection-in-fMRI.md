---
layout: post
title: "A simple and objective method for reproducible resting state network detection in fMRI"
date: 2011-08-10 19:02:29
categories: arXiv_CV
tags: arXiv_CV Detection
author: Gautam V. Pendse, David Borsook, Lino Becerra
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial Independent Component Analysis (ICA) decomposes the time by space functional MRI (fMRI) matrix into a set of 1-D basis time courses and their associated 3-D spatial maps that are optimized for mutual independence. When applied to resting state fMRI (rsfMRI), ICA produces several spatial independent components (ICs) that seem to have biological relevance - the so-called resting state networks (RSNs). The ICA problem is well posed when the true data generating process follows a linear mixture of ICs model in terms of the identifiability of the mixing matrix. However, the contrast function used for promoting mutual independence in ICA is dependent on the finite amount of observed data and is potentially non-convex with multiple local minima. Hence, each run of ICA could produce potentially different IC estimates even for the same data. One technique to deal with this run-to-run variability of ICA was proposed by Yang et al. (2008) in their algorithm RAICAR which allows for the selection of only those ICs that have a high run-to-run reproducibility. We propose an enhancement to the original RAICAR algorithm that enables us to assign reproducibility p-values to each IC and allows for an objective assessment of both within subject and across subjects reproducibility. We call the resulting algorithm RAICAR-N (N stands for null hypothesis test), and we have applied it to publicly available human rsfMRI data (this http URL). Our reproducibility analyses indicated that many of the published RSNs in rsfMRI literature are highly reproducible. However, we found several other RSNs that are highly reproducible but not frequently listed in the literature.

##### Abstract (translated by Google)
空间独立分量分析（ICA）通过空间功能MRI（fMRI）矩阵将时间分解为一组一维时间过程及其相关的三维空间映射，这些空间映射针对相互独立性进行了优化。当应用于静息状态fMRI（rsfMRI）时，ICA产生几个似乎与生物相关的空间独立分量（IC） - 所谓的静息状态网络（RSN）。当真实的数据生成过程遵循混合矩阵的可识别性的IC模型的线性混合时，ICA问题是很好的。然而，用于促进ICA相互独立的对比函数取决于观测数据的有限数量，并且可能具有多个局部最小值的非凸。因此，即使对于相同的数据，ICA的每次运行都可能产生可能不同的IC估计。 Yang等人提出了一种处理ICA这种跑步变异性的方法。 （2008）的算法RAICAR，它只允许选择那些具有高运行重复性的IC。我们建议对原始RAICAR算法进行改进，使我们能够将可重复性p值分配给每个IC，并允许对受试者和受试者重复性进行客观评估。我们将所得到的算法称为RAICAR-N（N代表虚假设检验），并将其应用于公开的人类rsfMRI数据（此http URL）。我们的重复性分析表明，rsfMRI文献中的许多已发表的RSN具有高重现性。然而，我们发现其他几个RSNs是高度可重复的，但不经常在文献中列出。

##### URL
[https://arxiv.org/abs/1108.2248](https://arxiv.org/abs/1108.2248)

##### PDF
[https://arxiv.org/pdf/1108.2248](https://arxiv.org/pdf/1108.2248)

