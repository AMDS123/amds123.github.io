---
layout: post
title: "GPU-Based Computation of 2D Least Median of Squares with Applications to Fast and Robust Line Detection"
date: 2015-10-05 06:38:03
categories: arXiv_CV
tags: arXiv_CV Detection
author: Gil Shapira, Tal Hassner
mathjax: true
---

* content
{:toc}

##### Abstract
The 2D Least Median of Squares (LMS) is a popular tool in robust regression because of its high breakdown point: up to half of the input data can be contaminated with outliers without affecting the accuracy of the LMS estimator. The complexity of 2D LMS estimation has been shown to be $\Omega(n^2)$ where $n$ is the total number of points. This high theoretical complexity along with the availability of graphics processing units (GPU) motivates the development of a fast, parallel, GPU-based algorithm for LMS computation. We present a CUDA based algorithm for LMS computation and show it to be much faster than the optimal state of the art single threaded CPU algorithm. We begin by describing the proposed method and analyzing its performance. We then demonstrate how it can be used to modify the well-known Hough Transform (HT) in order to efficiently detect image lines in noisy images. Our method is compared with standard HT-based line detection methods and shown to overcome their shortcomings in terms of both efficiency and accuracy.

##### Abstract (translated by Google)
二维平方最小中值法（LMS）是一种在鲁棒回归中受欢迎的工具，因为其高分解点：高达一半的输入数据可能被异常值污染而不影响LMS估计器的准确度。二维LMS估计的复杂性已经显示为$ \ Omega（n ^ 2）$，其中$ n $是总点数。这种高度的理论复杂性以及图形处理单元（GPU）的可用性激发了用于LMS计算的快速，并行，基于GPU的算法的发展。我们提出了一个基于CUDA的LMS计算算法，并显示它比最先进的单线程CPU算法的状态快得多。我们首先描述所提出的方法并分析其性能。然后，我们演示如何使用它来修改众所周知的霍夫变换（HT），以便在噪声图像中有效检测图像线条。我们的方法与标准的基于HT的在线检测方法进行了比较，显示了它们在效率和准确性方面的缺点。

##### URL
[https://arxiv.org/abs/1510.01041](https://arxiv.org/abs/1510.01041)

##### PDF
[https://arxiv.org/pdf/1510.01041](https://arxiv.org/pdf/1510.01041)

