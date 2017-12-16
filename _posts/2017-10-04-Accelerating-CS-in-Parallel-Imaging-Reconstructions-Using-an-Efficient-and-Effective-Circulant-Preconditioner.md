---
layout: post
title: "Accelerating CS in Parallel Imaging Reconstructions Using an Efficient and Effective Circulant Preconditioner"
date: 2017-10-04 18:48:20
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Kirsten Koolstra (1), Jeroen van Gemert (2), Peter Börnert (1 and 3), Andrew Webb (1), Rob Remis (2) ((1) C. J. Gorter Center for High Field MRI, Department of Radiology, Leiden University Medical Center, The Netherlands. (2) Circuits and Systems Group of the Electrical Engineering, Mathematics and Computer Science faculty of the Delft University of Technology, The Netherlands. (3) Philips Research Hamburg, Germany.)
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Design of a preconditioner for fast and efficient parallel imaging and compressed sensing reconstructions. Theory: Parallel imaging and compressed sensing reconstructions become time consuming when the problem size or the number of coils is large, due to the large linear system of equations that has to be solved in l_1 and l_2-norm based reconstruction algorithms. Such linear systems can be solved efficiently using effective preconditioning techniques. Methods: In this paper we construct such a preconditioner by approximating the system matrix of the linear system, which comprises the data fidelity and includes total variation and wavelet regularization, by a matrix with the assumption that is a block circulant matrix with circulant blocks. Due to its circulant structure, the preconditioner can be constructed quickly and its inverse can be evaluated fast using only two fast Fourier transformations. We test the performance of the preconditioner for the conjugate gradient method as the linear solver, integrated into the Split Bregman algorithm. Results: The designed circulant preconditioner reduces the number of iterations required in the conjugate gradient method by almost a factor of~5. The speed up results in a total acceleration factor of approximately 2.5 for the entire reconstruction algorithm when implemented in MATLAB, while the initialization time of the preconditioner is negligible. Conclusion: The proposed preconditioner reduces the reconstruction time for parallel imaging and compressed sensing in a Split Bregman implementation and can easily handle large systems since it is Fourier-based, allowing for efficient computations. Key words: preconditioning; compressed sensing; Split Bregman; parallel imaging

##### Abstract (translated by Google)
目的：设计快速高效的并行成像和压缩感测重建的预处理器。理论：由于需要在基于l_1和l_2范数的重建算法中求解的大线性方程组，所以并行成像和压缩感测重建在问题尺寸或线圈数量很大时变得耗时。使用有效的预处理技术可以有效地解决这样的线性系统。方法：本文通过一个矩阵的假设，即具有循环块的块循环矩阵，通过近似包含数据保真度（包括总变差和小波正则化）的线性系统的系统矩阵来构造这样的预处理器。由于其循环结构，预处理器可以快速构建，并且仅使用两次快速傅里叶变换就可以快速地对其求逆。我们作为线性求解器测试了共轭梯度法的预处理器的性能，并将其结合到了Split Bregman算法中。结果：设计的循环预处理器将共轭梯度法中所需的迭代次数减少了近5倍。在MATLAB中实现整个重建算法时，加速导致总加速因子约为2.5，而预处理器的初始化时间可以忽略不计。结论：所提出的预处理器减少了分裂布雷格曼实现中并行成像和压缩感测的重建时间，并且可以容易地处理大型系统，因为它是基于傅立叶的，从而允许有效的计算。关键词：预处理;压缩感测;分裂Bregman;平行成像

##### URL
[https://arxiv.org/abs/1710.01758](https://arxiv.org/abs/1710.01758)

##### PDF
[https://arxiv.org/pdf/1710.01758](https://arxiv.org/pdf/1710.01758)

