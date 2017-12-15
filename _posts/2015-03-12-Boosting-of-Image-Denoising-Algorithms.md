---
layout: post
title: "Boosting of Image Denoising Algorithms"
date: 2015-03-12 13:49:42
categories: arXiv_CV
tags: arXiv_CV
author: Yaniv Romano, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a generic recursive algorithm for improving image denoising methods. Given the initial denoised image, we suggest repeating the following "SOS" procedure: (i) (S)trengthen the signal by adding the previous denoised image to the degraded input image, (ii) (O)perate the denoising method on the strengthened image, and (iii) (S)ubtract the previous denoised image from the restored signal-strengthened outcome. The convergence of this process is studied for the K-SVD image denoising and related algorithms. Still in the context of K-SVD image denoising, we introduce an interesting interpretation of the SOS algorithm as a technique for closing the gap between the local patch-modeling and the global restoration task, thereby leading to improved performance. In a quest for the theoretical origin of the SOS algorithm, we provide a graph-based interpretation of our method, where the SOS recursive update effectively minimizes a penalty function that aims to denoise the image, while being regularized by the graph Laplacian. We demonstrate the SOS boosting algorithm for several leading denoising methods (K-SVD, NLM, BM3D, and EPLL), showing tendency to further improve denoising performance.

##### Abstract (translated by Google)
在本文中，我们提出了一种改进图像去噪方法的通用递归算法。 （S）通过将先前的去噪后的图像添加到退化的输入图像中来增强信号，（ii）（O）对增强后的图像进行去噪处理图像，和（iii）（S）从恢复的信号强化结果中提取以前的去噪图像。针对K-SVD图像去噪和相关算法研究了该过程的收敛性。仍然在K-SVD图像去噪的背景下，我们引入了SOS算法的一个有趣的解释，作为缩小局部补丁建模和全局恢复任务之间差距的一种技术，从而提高了性能。为了寻求SOS算法的理论起源，我们提供了一种基于图形的解释方法，其中SOS递归更新有效地最小化旨在去噪图像的惩罚函数，同时被拉普拉斯算子调整。我们演示了几种领先的去噪方法（K-SVD，NLM，BM3D和EPLL）的SOS提升算法，显示出进一步提高去噪性能的趋势。

##### URL
[https://arxiv.org/abs/1502.06220](https://arxiv.org/abs/1502.06220)

##### PDF
[https://arxiv.org/pdf/1502.06220](https://arxiv.org/pdf/1502.06220)

