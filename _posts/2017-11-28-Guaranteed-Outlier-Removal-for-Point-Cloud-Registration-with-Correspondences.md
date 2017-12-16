---
layout: post
title: "Guaranteed Outlier Removal for Point Cloud Registration with Correspondences"
date: 2017-11-28 10:02:18
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Álvaro Parra Bustos, Tat-Jun Chin
mathjax: true
---

* content
{:toc}

##### Abstract
An established approach for 3D point cloud registration is to estimate the registration function from 3D keypoint correspondences. Typically, a robust technique is required to conduct the estimation, since there are false correspondences or outliers. Current 3D keypoint techniques are much less accurate than their 2D counterparts, thus they tend to produce extremely high outlier rates. A large number of putative correspondences must thus be extracted to ensure that sufficient good correspondences are available. Both factors (high outlier rates, large data sizes) however cause existing robust techniques to require very high computational cost. In this paper, we present a novel preprocessing method called \emph{guaranteed outlier removal} for point cloud registration. Our method reduces the input to a smaller set, in a way that any rejected correspondence is guaranteed to not exist in the globally optimal solution. The reduction is performed using purely geometric operations which are deterministic and fast. Our method significantly reduces the population of outliers, such that further optimization can be performed quickly. Further, since only true outliers are removed, the globally optimal solution is preserved. On various synthetic and real data experiments, we demonstrate the effectiveness of our preprocessing method. Demo code is available as supplementary material.

##### Abstract (translated by Google)
建立三维点云配准方法是从三维关键点对应关系估计配准函数。通常情况下，需要一个强大的技术来进行估计，因为有错误的对应关系或异常值。当前的三维关键点技术比二维的关键点技术要精确得多，因此往往会产生极高的异常值。因此，必须提取大量假定的信件，以确保有足够的良好信件。然而，这两个因素（高异常率，大数据量）都会导致现有的强大技术需要非常高的计算成本。在本文中，我们提出了一种新的预处理方法，称为\ emph {保证异常值删除}点云登记。我们的方法将输入减少到一个较小的集合，从而保证在全局最优解中不存在被拒绝的对应关系。减少是使用确定性和快速的纯几何操作来执行的。我们的方法大大减少了异常值的数量，从而可以快速进行进一步的优化。此外，由于只有真正的异常值被删除，全局最优解得以保留。在各种合成和实际的数据实验中，我们证明了我们的预处理方法的有效性。演示代码可作为补充材料。

##### URL
[https://arxiv.org/abs/1711.10209](https://arxiv.org/abs/1711.10209)

##### PDF
[https://arxiv.org/pdf/1711.10209](https://arxiv.org/pdf/1711.10209)

