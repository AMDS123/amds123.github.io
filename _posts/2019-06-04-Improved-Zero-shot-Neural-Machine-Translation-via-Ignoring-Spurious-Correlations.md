---
layout: post
title: "Improved Zero-shot Neural Machine Translation via Ignoring Spurious Correlations"
date: 2019-06-04 03:30:22
categories: arXiv_CL
tags: arXiv_CL NMT Quantitative Relation
author: Jiatao Gu, Yong Wang, Kyunghyun Cho, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot translation, translating between language pairs on which a Neural Machine Translation (NMT) system has never been trained, is an emergent property when training the system in multilingual settings. However, naive training for zero-shot NMT easily fails, and is sensitive to hyper-parameter setting. The performance typically lags far behind the more conventional pivot-based approach which translates twice using a third language as a pivot. In this work, we address the degeneracy problem due to capturing spurious correlations by quantitatively analyzing the mutual information between language IDs of the source and decoded sentences. Inspired by this analysis, we propose to use two simple but effective approaches: (1) decoder pre-training; (2) back-translation. These methods show significant improvement (4~22 BLEU points) over the vanilla zero-shot translation on three challenging multilingual datasets, and achieve similar or better results than the pivot-based approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01181](http://arxiv.org/abs/1906.01181)

##### PDF
[http://arxiv.org/pdf/1906.01181](http://arxiv.org/pdf/1906.01181)

