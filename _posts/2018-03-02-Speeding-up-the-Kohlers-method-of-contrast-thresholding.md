---
layout: post
title: "Speeding up the K'ohler's method of contrast thresholding"
date: 2018-03-02 10:43:48
categories: arXiv_CV
tags: arXiv_CV
author: Guillaume Noyel (IPRI, SIGPH@iPRI)
mathjax: true
---

* content
{:toc}

##### Abstract
K{\"o}hler's method is a useful multi-thresholding technique based on boundary contrast. However, the direct algorithm has a too high complexity-O(N 2) i.e. quadratic with the pixel numbers N-to process images at a sufficient speed for practical applications. In this paper, a new algorithm to speed up K{\"o}hler's method is introduced with a complexity in O(N M), M is the number of grey levels. The proposed algorithm is designed for parallelisation and vector processing , which are available in current processors, using OpenMP (Open Multi-Processing) and SIMD instructions (Single Instruction on Multiple Data). A fast implementation allows a gain factor of 405 in an image of 18 million pixels and a video processing in real time (gain factor of 96).

##### Abstract (translated by Google)
K（o）hler的方法是基于边界对比度的一种有用的多阈值技术，然而，直接算法具有太高的复杂度--O（N 2），即像素数为N的二次方，以足够处理图像本文提出了一种加速K（o）hler方法的新算法，其复杂度为O（NM），M为灰度级数。所提出的算法被设计用于在当前处理器中使用OpenMP（开放式多处理）和SIMD指令（单指令多数据）的并行化和矢量处理。快速实现允许1800万像素图像中的增益因子为405，实时视频处理（增益因子为96）。

##### URL
[http://arxiv.org/abs/1707.05062](http://arxiv.org/abs/1707.05062)

##### PDF
[http://arxiv.org/pdf/1707.05062](http://arxiv.org/pdf/1707.05062)

