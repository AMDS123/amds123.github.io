---
layout: post
title: "Active Canny: Edge Detection and Recovery with Open Active Contour Models"
date: 2016-09-12 14:13:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Muhammet Bastan, S. Saqib Bukhari, Thomas M. Breuel
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an edge detection and recovery framework based on open active contour models (snakelets). This is motivated by the noisy or broken edges output by standard edge detection algorithms, like Canny. The idea is to utilize the local continuity and smoothness cues provided by strong edges and grow them to recover the missing edges. This way, the strong edges are used to recover weak or missing edges by considering the local edge structures, instead of blindly linking them if gradient magnitudes are above some threshold. We initialize short snakelets on the gradient magnitudes or binary edges automatically and then deform and grow them under the influence of gradient vector flow. The output snakelets are able to recover most of the breaks or weak edges, and they provide a smooth edge representation of the image; they can also be used for higher level analysis, like contour segmentation.

##### Abstract (translated by Google)
我们引入一个基于开放主动轮廓模型（snakelets）的边缘检测和恢复框架。这是由标准边缘检测算法（如Canny）输出的噪声或破碎边缘所驱动的。这个想法是利用强边缘提供的局部连续性和平滑性线索来增长它们以恢复缺失的边缘。这样，强边就可以通过考虑局部边缘结构来恢复弱边或缺失边，而不是在梯度幅度高于某个阈值时盲目链接它们。我们在梯度幅度或二值边缘上自动初始化短小蛇，然后在梯度矢量流的影响下变形和增长它们。输出snakelets能够恢复大部分的中断或弱边缘，并且它们提供图像的平滑边缘表示;它们也可以用于更高级别的分析，如轮廓分割。

##### URL
[https://arxiv.org/abs/1609.03415](https://arxiv.org/abs/1609.03415)

##### PDF
[https://arxiv.org/pdf/1609.03415](https://arxiv.org/pdf/1609.03415)

