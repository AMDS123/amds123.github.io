---
layout: post
title: "ANSAC: Adaptive Non-minimal Sample and Consensus"
date: 2017-09-27 14:47:03
categories: arXiv_CV
tags: arXiv_CV
author: Victor Fragoso, Chris Sweeney, Pradeep Sen, Matthew Turk
mathjax: true
---

* content
{:toc}

##### Abstract
While RANSAC-based methods are robust to incorrect image correspondences (outliers), their hypothesis generators are not robust to correct image correspondences (inliers) with positional error (noise). This slows down their convergence because hypotheses drawn from a minimal set of noisy inliers can deviate significantly from the optimal model. This work addresses this problem by introducing ANSAC, a RANSAC-based estimator that accounts for noise by adaptively using more than the minimal number of correspondences required to generate a hypothesis. ANSAC estimates the inlier ratio (the fraction of correct correspondences) of several ranked subsets of candidate correspondences and generates hypotheses from them. Its hypothesis-generation mechanism prioritizes the use of subsets with high inlier ratio to generate high-quality hypotheses. ANSAC uses an early termination criterion that keeps track of the inlier ratio history and terminates when it has not changed significantly for a period of time. The experiments show that ANSAC finds good homography and fundamental matrix estimates in a few iterations, consistently outperforming state-of-the-art methods.

##### Abstract (translated by Google)
虽然基于RANSAC的方法对于不正确的图像对应（异常值）是鲁棒的，但是它们的假设生成器对于用位置误差（噪声）校正图像对应（内部）是不稳健的。这减慢了它们的收敛速度，因为从最小的嘈杂的内点集合中得出的假设可能显着偏离最优模型。这项工作通过引入ANSAC（一种基于RANSAC的估计器来解决这个问题）来解决噪声问题，这种估计器通过自适应地使用多于产生假设所需的最少数量的对应关系来解决噪声问题。 ANSAC估计候选对应关系的几个等级子集的内点比率（正确对应关系的比例），并从中产生假设。其假设生成机制优先使用高比例的子集来生成高质量的假设。 ANSAC使用一个提前的终止标准来跟踪inlier比例历史，并在一段时间内没有显着变化时终止。实验表明，ANSAC在几次迭代中找到了良好的单应矩阵和基本矩阵估计，始终超越最先进的方法。

##### URL
[https://arxiv.org/abs/1709.09559](https://arxiv.org/abs/1709.09559)

##### PDF
[https://arxiv.org/pdf/1709.09559](https://arxiv.org/pdf/1709.09559)

