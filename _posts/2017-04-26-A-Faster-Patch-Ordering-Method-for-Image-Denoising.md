---
layout: post
title: "A Faster Patch Ordering Method for Image Denoising"
date: 2017-04-26 13:06:56
categories: arXiv_CV
tags: arXiv_CV
author: Badre Munir
mathjax: true
---

* content
{:toc}

##### Abstract
Among the patch-based image denoising processing methods, smooth ordering of local patches (patch ordering) has been shown to give state-of-art results. For image denoising the patch ordering method forms two large TSPs (Traveling Salesman Problem) comprised of nodes in N-dimensional space. Ten approximate solutions of the two large TSPs are then used in a filtering process to form the reconstructed image. Use of large TSPs makes patch ordering a computationally intensive method. A modified patch ordering method for image denoising is proposed. In the proposed method, several smaller-sized TSPs are formed and the filtering process varied to work with solutions of these smaller TSPs. In terms of PSNR, denoising results of the proposed method differed by 0.032 dB to 0.016 dB on average. In original method, solving TSPs was observed to consume 85% of execution time. In proposed method, the time for solving TSPs can be reduced to half of the time required in original method. The proposed method can denoise images in 40% less time.

##### Abstract (translated by Google)
在基于斑块的图像去噪处理方法中，已经证明局部斑块的平滑排序（斑块排序）给出了最新的结果。对于图像去噪，面片排序方法形成了由N维空间中的节点组成的两个大的TSP（旅行推销员问题）。然后在滤波过程中使用两个大的TSP的十个近似解来形成重构图像。大型TSP的使用使修补程序排序计算密集型的方法。提出了一种改进的图像去噪贴片排序方法。在所提出的方法中，形成了几个较小尺寸的TSP，并且滤波过程变化以与这些较小的TSP的解决方案一起工作。在PSNR方面，所提出的方法的去噪结果平均相差0.032dB至0.016dB。在原来的方法，解决TSPs被观察到消耗85％的执行时间。在提出的方法中，解决TSPs的时间可以缩短到原始方法所需时间的一半。该方法可以减少40％的图像去噪。

##### URL
[https://arxiv.org/abs/1704.08090](https://arxiv.org/abs/1704.08090)

##### PDF
[https://arxiv.org/pdf/1704.08090](https://arxiv.org/pdf/1704.08090)

