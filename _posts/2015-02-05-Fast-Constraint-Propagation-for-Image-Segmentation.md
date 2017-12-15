---
layout: post
title: "Fast Constraint Propagation for Image Segmentation"
date: 2015-02-05 09:41:28
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Peng Han
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel selective constraint propagation method for constrained image segmentation. In the literature, many pairwise constraint propagation methods have been developed to exploit pairwise constraints for cluster analysis. However, since most of these methods have a polynomial time complexity, they are not much suitable for segmentation of images even with a moderate size, which is actually equivalent to cluster analysis with a large data size. Considering the local homogeneousness of a natural image, we choose to perform pairwise constraint propagation only over a selected subset of pixels, but not over the whole image. Such a selective constraint propagation problem is then solved by an efficient graph-based learning algorithm. To further speed up our selective constraint propagation, we also discard those less important propagated constraints during graph-based learning. Finally, the selectively propagated constraints are exploited based on $L_1$-minimization for normalized cuts over the whole image. The experimental results demonstrate the promising performance of the proposed method for segmentation with selectively propagated constraints.

##### Abstract (translated by Google)
本文提出了一种新的选择性约束传播方法用于约束图像分割。在文献中，已经开发了许多成对约束传播方法来利用成对约束进行聚类分析。然而，由于这些方法中的大多数具有多项式时间复杂度，所以即使具有适中的大小也不太适合于图像的分割，这实际上相当于具有大数据大小的聚类分析。考虑到自然图像的局部均匀性，我们选择仅在选定的像素子集上执行成对约束传播，而不是在整个图像上进行。然后通过高效的基于图的学​​习算法来解决这种选择性约束传播问题。为了进一步加速我们的选择性约束传播，我们也放弃了基于图形学习的那些不太重要的传播约束。最后，选择性传播的约束是基于$ L_1 $最小化对整个图像进行归一化切割。实验结果证明了所提出的选择性传播约束分割方法的有前途的性能。

##### URL
[https://arxiv.org/abs/1502.01475](https://arxiv.org/abs/1502.01475)

##### PDF
[https://arxiv.org/pdf/1502.01475](https://arxiv.org/pdf/1502.01475)

