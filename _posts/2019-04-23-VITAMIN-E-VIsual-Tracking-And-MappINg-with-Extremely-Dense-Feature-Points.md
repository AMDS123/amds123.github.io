---
layout: post
title: "VITAMIN-E: VIsual Tracking And MappINg with Extremely Dense Feature Points"
date: 2019-04-23 13:39:10
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization SLAM
author: Masashi Yokozuka, Shuji Oishi, Thompson Simon, Atsuhiko Banno
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel indirect monocular SLAM algorithm called "VITAMIN-E," which is highly accurate and robust as a result of tracking extremely dense feature points. Typical indirect methods have difficulty in reconstructing dense geometry because of their careful feature point selection for accurate matching. Unlike conventional methods, the proposed method processes an enormous number of feature points by tracking the local extrema of curvature informed by dominant flow estimation. Because this may lead to high computational cost during bundle adjustment, we propose a novel optimization technique, the "subspace Gauss--Newton method", that significantly improves the computational efficiency of bundle adjustment by partially updating the variables. We concurrently generate meshes from the reconstructed points and merge them for an entire 3D model. The experimental results on the SLAM benchmark dataset EuRoC demonstrated that the proposed method outperformed state-of-the-art SLAM methods, such as DSO, ORB-SLAM, and LSD-SLAM, both in terms of accuracy and robustness in trajectory estimation. The proposed method simultaneously generated significantly detailed 3D geometry from the dense feature points in real time using only a CPU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10324](http://arxiv.org/abs/1904.10324)

##### PDF
[http://arxiv.org/pdf/1904.10324](http://arxiv.org/pdf/1904.10324)

