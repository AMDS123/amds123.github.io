---
layout: post
title: "The Parallel Algorithm for the 2-D Discrete Wavelet Transform"
date: 2017-09-26 07:19:38
categories: arXiv_CV
tags: arXiv_CV
author: David Barina, Pavel Najman, Petr Kleparnik, Michal Kula, Pavel Zemcik
mathjax: true
---

* content
{:toc}

##### Abstract
The discrete wavelet transform can be found at the heart of many image-processing algorithms. Until now, the transform on general-purpose processors (CPUs) was mostly computed using a separable lifting scheme. As the lifting scheme consists of a small number of operations, it is preferred for processing using single-core CPUs. However, considering a parallel processing using multi-core processors, this scheme is inappropriate due to a large number of steps. On such architectures, the number of steps corresponds to the number of points that represent the exchange of data. Consequently, these points often form a performance bottleneck. Our approach appropriately rearranges calculations inside the transform, and thereby reduces the number of steps. In other words, we propose a new scheme that is friendly to parallel environments. When evaluating on multi-core CPUs, we consistently overcome the original lifting scheme. The evaluation was performed on 61-core Intel Xeon Phi and 8-core Intel Xeon processors.

##### Abstract (translated by Google)
离散小波变换可以在许多图像处理算法的核心中找到。到目前为止，通用处理器（CPU）上的转换主要是使用可分离的提升方案计算的。由于提升方案由少量操作组成，因此最好使用单核CPU进行处理。然而，考虑到使用多核处理器的并行处理，该方案由于步骤数量大而不合适。在这样的体系结构中，步数与代表数据交换的点的数量相对应。因此，这些点经常会形成性能瓶颈。我们的方法适当地重新安排变换内部的计算，从而减少步骤的数量。换句话说，我们提出了一个对并行环境友好的新方案。在评估多核CPU时，我们一直在克服原来的升级方案。评估是在61核英特尔至强融核和8核英特尔至强处理器上进行的。

##### URL
[https://arxiv.org/abs/1708.07853](https://arxiv.org/abs/1708.07853)

##### PDF
[https://arxiv.org/pdf/1708.07853](https://arxiv.org/pdf/1708.07853)

