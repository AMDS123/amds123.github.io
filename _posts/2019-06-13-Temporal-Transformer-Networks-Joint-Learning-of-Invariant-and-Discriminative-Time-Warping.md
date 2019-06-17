---
layout: post
title: "Temporal Transformer Networks: Joint Learning of Invariant and Discriminative Time Warping"
date: 2019-06-13 22:05:15
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Suhas Lohit, Qiao Wang, Pavan Turaga
mathjax: true
---

* content
{:toc}

##### Abstract
Many time-series classification problems involve developing metrics that are invariant to temporal misalignment. In human activity analysis, temporal misalignment arises due to various reasons including differing initial phase, sensor sampling rates, and elastic time-warps due to subject-specific biomechanics. Past work in this area has only looked at reducing intra-class variability by elastic temporal alignment. In this paper, we propose a hybrid model-based and data-driven approach to learn warping functions that not just reduce intra-class variability, but also increase inter-class separation. We call this a temporal transformer network (TTN). TTN is an interpretable differentiable module, which can be easily integrated at the front end of a classification network. The module is capable of reducing intra-class variance by generating input-dependent warping functions which lead to rate-robust representations. At the same time, it increases inter-class variance by learning warping functions that are more discriminative. We show improvements over strong baselines in 3D action recognition on challenging datasets using the proposed framework. The improvements are especially pronounced when training sets are smaller.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05947](https://arxiv.org/abs/1906.05947)

##### PDF
[https://arxiv.org/pdf/1906.05947](https://arxiv.org/pdf/1906.05947)

