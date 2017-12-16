---
layout: post
title: "Accurate Motion Estimation through Random Sample Aggregated Consensus"
date: 2017-01-19 01:13:41
categories: arXiv_CV
tags: arXiv_CV
author: Martin Rais, Gabriele Facciolo, Enric Meinhardt-Llopis, Jean-Michel Morel, Antoni Buades, Bartomeu Coll
mathjax: true
---

* content
{:toc}

##### Abstract
We reconsider the classic problem of estimating accurately a 2D transformation from point matches between images containing outliers. RANSAC discriminates outliers by randomly generating minimalistic sampled hypotheses and verifying their consensus over the input data. Its response is based on the single hypothesis that obtained the largest inlier support. In this article we show that the resulting accuracy can be improved by aggregating all generated hypotheses. This yields RANSAAC, a framework that improves systematically over RANSAC and its state-of-the-art variants by statistically aggregating hypotheses. To this end, we introduce a simple strategy that allows to rapidly average 2D transformations, leading to an almost negligible extra computational cost. We give practical applications on projective transforms and homography+distortion models and demonstrate a significant performance gain in both cases.

##### Abstract (translated by Google)
我们重新考虑一个典型的问题，即从包含异常值的图像之间的点匹配中精确地估计2D变换。 RANSAC通过随机产生极简抽样假设并验证他们对输入数据的一致性来区分异常值。其反应是基于获得最大内部支持的单一假设。在这篇文章中，我们展示了通过聚合所有生成的假设可以提高结果的准确性。这产生了RANSAAC，这是一个通过统计汇总假设而系统地改进RANSAC及其最新技术变体的框架。为此，我们引入一个简单的策略，允许快速平均2D变换，导致几乎可以忽略的额外的计算成本。我们给出了投影变换和单应性+失真模型的实际应用，并且在两种情况下都显示出显着的性能增益。

##### URL
[https://arxiv.org/abs/1701.05268](https://arxiv.org/abs/1701.05268)

##### PDF
[https://arxiv.org/pdf/1701.05268](https://arxiv.org/pdf/1701.05268)

