---
layout: post
title: "Road surface 3d reconstruction based on dense subpixel disparity map estimation"
date: 2018-07-05 07:13:42
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Rui Fan, Xiao Ai, Naim Dahnoun
mathjax: true
---

* content
{:toc}

##### Abstract
Various 3D reconstruction methods have enabled civil engineers to detect damage on a road surface. To achieve the millimetre accuracy required for road condition assessment, a disparity map with subpixel resolution needs to be used. However, none of the existing stereo matching algorithms are specially suitable for the reconstruction of the road surface. Hence in this paper, we propose a novel dense subpixel disparity estimation algorithm with high computational efficiency and robustness. This is achieved by first transforming the perspective view of the target frame into the reference view, which not only increases the accuracy of the block matching for the road surface but also improves the processing speed. The disparities are then estimated iteratively using our previously published algorithm where the search range is propagated from three estimated neighbouring disparities. Since the search range is obtained from the previous iteration, errors may occur when the propagated search range is not sufficient. Therefore, a correlation maxima verification is performed to rectify this issue, and the subpixel resolution is achieved by conducting a parabola interpolation enhancement. Furthermore, a novel disparity global refinement approach developed from the Markov Random Fields and Fast Bilateral Stereo is introduced to further improve the accuracy of the estimated disparity map, where disparities are updated iteratively by minimising the energy function that is related to their interpolated correlation polynomials. The algorithm is implemented in C language with a near real-time performance. The experimental results illustrate that the absolute error of the reconstruction varies from 0.1 mm to 3 mm.

##### Abstract (translated by Google)
各种3D重建方法使土木工程师能够检测到路面上的损坏。为了实现道路状况评估所需的毫米精度，需要使用具有子像素分辨率的视差图。然而，现有的立体匹配算法都不是特别适合于路面的重建。因此，在本文中，我们提出了一种具有高计算效率和鲁棒性的新型密集子像素视差估计算法。这是通过首先将目标框架的透视图变换为参考视图来实现的，这不仅提高了路面的块匹配精度，而且提高了处理速度。然后使用我们先前公布的算法迭代地估计差异，其中搜索范围从三个估计的相邻差异传播。由于搜索范围是从前一次迭代获得的，因此当传播的搜索范围不足时可能发生错误。因此，执行相关最大值验证以纠正该问题，并且通过进行抛物线内插增强来实现子像素分辨率。此外，引入了从马尔可夫随机场和快速双边立体声开发的新颖视差全局细化方法，以进一步提高估计视差图的准确度，其中通过最小化与其内插相关多项式相关的能量函数来迭代地更新视差。该算法以C语言实现，具有接近实时的性能。实验结果表明，重建的绝对误差从0.1 mm到3 mm不等。

##### URL
[http://arxiv.org/abs/1807.01874](http://arxiv.org/abs/1807.01874)

##### PDF
[http://arxiv.org/pdf/1807.01874](http://arxiv.org/pdf/1807.01874)

