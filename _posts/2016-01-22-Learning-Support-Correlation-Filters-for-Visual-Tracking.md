---
layout: post
title: "Learning Support Correlation Filters for Visual Tracking"
date: 2016-01-22 15:02:50
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Relation
author: Wangmeng Zuo, Xiaohe Wu, Liang Lin, Lei Zhang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Sampling and budgeting training examples are two essential factors in tracking algorithms based on support vector machines (SVMs) as a trade-off between accuracy and efficiency. Recently, the circulant matrix formed by dense sampling of translated image patches has been utilized in correlation filters for fast tracking. In this paper, we derive an equivalent formulation of a SVM model with circulant matrix expression and present an efficient alternating optimization method for visual tracking. We incorporate the discrete Fourier transform with the proposed alternating optimization process, and pose the tracking problem as an iterative learning of support correlation filters (SCFs) which find the global optimal solution with real-time performance. For a given circulant data matrix with n^2 samples of size n*n, the computational complexity of the proposed algorithm is O(n^2*logn) whereas that of the standard SVM-based approaches is at least O(n^4). In addition, we extend the SCF-based tracking algorithm with multi-channel features, kernel functions, and scale-adaptive approaches to further improve the tracking performance. Experimental results on a large benchmark dataset show that the proposed SCF-based algorithms perform favorably against the state-of-the-art tracking methods in terms of accuracy and speed.

##### Abstract (translated by Google)
采样和预算训练实例是基于支持向量机（SVM）跟踪算法的两个关键因素，即精度和效率之间的折衷。最近，通过密集采样翻译图像块形成的循环矩阵已被用于相关滤波器中用于快速跟踪。在本文中，我们推导了一个具有循环矩阵表达式的SVM模型的等价表达式，并提出了一种有效的视觉跟踪交替优化方法。将离散傅里叶变换与交错优化过程相结合，将跟踪问题作为支持向量相关滤波器（SCFs）的迭代学习算法，实现了具有实时性能的全局最优解。对于一个n * 2个大小为n * n个样本的循环数据矩阵，所提出算法的计算复杂度为O（n ^ 2 * logn），而标准SVM方法的计算复杂度至少为O（n ^ 4 ）。此外，我们还扩展了基于SCF的多通道特征跟踪算法，核函数和尺度自适应算法，以进一步提高跟踪性能。在大型基准数据集上的实验结果表明，所提出的基于SCF的算法在准确性和速度方面优于现有技术的跟踪方法。

##### URL
[https://arxiv.org/abs/1601.06032](https://arxiv.org/abs/1601.06032)

##### PDF
[https://arxiv.org/pdf/1601.06032](https://arxiv.org/pdf/1601.06032)

