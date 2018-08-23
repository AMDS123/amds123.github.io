---
layout: post
title: "Faster PET Reconstruction with Non-Smooth Priors by Randomization and Preconditioning"
date: 2018-08-21 22:19:37
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Matthias J. Ehrhardt, Pawel Markiewicz, Carola-Bibiane Sch&#xf6;nlieb
mathjax: true
---

* content
{:toc}

##### Abstract
Uncompressed clinical data from modern positron emission tomography (PET) scanners are very large, exceeding 300 million data points. The last decades have seen tremendous advancements in mathematical imaging tools many of which lead to non-smooth optimization problems. Most of these tools have not been translated to clinical PET data, as the algorithms for non-smooth problems do not scale well enough for large data sets. In this work, inspired by big data machine learning applications, we use advanced randomized optimization algorithms to solve the PET reconstruction problem for a very large class of non-smooth priors which includes for example total variation, total generalized variation, directional total variation and many constraints. We show on real PET data (FDG and florbetapir) from the Siemens Biograph mMR that a dozen forward (and back) projections are sufficient, thus showing that this algorithm is fast enough to bring these models into clinical practice. Moreover, the proposed algorithm is similarly fast on the unregularized problem as the clinical standard OSEM but, in contrast to OSEM, has provable convergence guarantees, robustness and stability for any subset selection.

##### Abstract (translated by Google)
来自现代正电子发射断层扫描（PET）扫描仪的未压缩临床数据非常大，超过3亿个数据点。在过去的几十年中，数学成像工具取得了巨大进步，其中许多工具导致了不平滑的优化问题。大多数这些工具尚未转化为临床PET数据，因为非平滑问题的算法不能很好地扩展到大数据集。在这项受大数据机器学习应用启发的工作中，我们使用先进的随机优化算法来解决非常大的非光滑先验的PET重建问题，包括例如总变差，总广义变化，方向总变差和许多限制。我们在西门子Biograph mMR的真实PET数据（FDG和florbetapir）上展示了十几个前向（和后向）投影就足够了，从而表明该算法足够快，可以将这些模型带入临床实践。此外，所提出的算法在与作为临床标准OSEM的非正规化问题上类似地快速，但是与OSEM相比，对于任何子集选择具有可证实的收敛保证，鲁棒性和稳定性。

##### URL
[http://arxiv.org/abs/1808.07150](http://arxiv.org/abs/1808.07150)

##### PDF
[http://arxiv.org/pdf/1808.07150](http://arxiv.org/pdf/1808.07150)

