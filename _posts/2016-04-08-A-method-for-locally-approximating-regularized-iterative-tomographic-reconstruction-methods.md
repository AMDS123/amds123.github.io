---
layout: post
title: "A method for locally approximating regularized iterative tomographic reconstruction methods"
date: 2016-04-08 10:19:20
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge
author: D. M. Pelt, K. J. Batenburg
mathjax: true
---

* content
{:toc}

##### Abstract
In many applications of tomography, the acquired projections are either limited in number or contain a significant amount of noise. In these cases, standard reconstruction methods tend to produce artifacts that can make further analysis difficult. Advanced regularized iterative methods, such as total variation minimization, are often able to achieve a higher reconstruction quality by exploiting prior knowledge about the scanned object. In practice, however, these methods often have prohibitively long computation times or large memory requirements. Furthermore, since they are based on minimizing a global objective function, regularized iterative methods need to reconstruct the entire scanned object, even when one is only interested in a (small) region of the reconstructed image. In this paper, we present a method to approximate regularized iterative reconstruction methods inside a (small) region of the scanned object. The method only performs computations inside the region of interest, ensuring low computational requirements. Reconstruction results for different phantom images and types of regularization are given, showing that reconstructions of the proposed local method are almost identical to those of the global regularized iterative methods that are approximated, even for relatively small regions of interest. Furthermore, we show that larger regions can be reconstructed efficiently by reconstructing several small regions in parallel and combining them into a single reconstruction afterwards.

##### Abstract (translated by Google)
在层析成像的许多应用中，所获得的投影在数量上是有限的或者包含大量的噪声。在这些情况下，标准重建方法倾向于产生可能使进一步分析困难的伪像。先进的正则化迭代方法，如总变差最小化，往往能够通过利用关于扫描对象的先验知识来实现​​更高的重建质量。然而实际上，这些方法通常具有非常长的计算时间或大的内存需求。此外，由于它们是基于使全局目标函数最小化的，所以正则化迭代方法需要重建整个扫描对象，即使当只对重建图像的（小）区域感兴趣时也是如此。在本文中，我们提出了一种近似正则化迭代重建方法在被扫描物体（小）区域内的方法。该方法仅在感兴趣区域内执行计算，确保低计算需求。给出了不同幻影图像和正则化类型的重建结果，表明所提出的局部方法的重构与全局正则化迭代方法的重构几乎相同，即使对于相对较小的感兴趣区域也是如此。此外，我们还表明，通过并行重建几个小区域，然后将它们组合成单个重建，可以有效地重建较大的区域。

##### URL
[https://arxiv.org/abs/1604.02292](https://arxiv.org/abs/1604.02292)

##### PDF
[https://arxiv.org/pdf/1604.02292](https://arxiv.org/pdf/1604.02292)

