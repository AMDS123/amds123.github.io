---
layout: post
title: "Hybrid Camera Pose Estimation with Online Partitioning"
date: 2019-08-05 18:26:03
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation Optimization
author: Xinyi Li, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a hybrid real-time camera pose estimation framework with a novel partitioning scheme and introduces motion averaging to on-line monocular systems. Breaking through the limitations of fixed-size temporal partitioning in most conventional pose estimation mechanisms, the proposed approach significantly improves the accuracy of local bundle adjustment by gathering spatially-strongly-connected cameras into each block. With the dynamic initialization using intermediate computation values, our proposed self-adaptive Levenberg-Marquardt solver achieves a quadratic convergence rate to further enhance the efficiency of the local optimization. Moreover, the dense data association between blocks by virtue of our co-visibility-based partitioning enables us to explore and implement motion averaging to efficiently align the blocks globally, updating camera motion estimations on-the-fly. Experiment results on benchmarks convincingly demonstrate the practicality and robustness of our proposed approach by outperforming conventional bundle adjustment by orders of magnitude.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.01797](https://arxiv.org/abs/1908.01797)

##### PDF
[https://arxiv.org/pdf/1908.01797](https://arxiv.org/pdf/1908.01797)

