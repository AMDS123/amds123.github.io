---
layout: post
title: "Efficient Dictionary Learning with Sparseness-Enforcing Projections"
date: 2016-04-16 15:42:12
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Optimization
author: Markus Thom, Matthias Rapp, Günther Palm
mathjax: true
---

* content
{:toc}

##### Abstract
Learning dictionaries suitable for sparse coding instead of using engineered bases has proven effective in a variety of image processing tasks. This paper studies the optimization of dictionaries on image data where the representation is enforced to be explicitly sparse with respect to a smooth, normalized sparseness measure. This involves the computation of Euclidean projections onto level sets of the sparseness measure. While previous algorithms for this optimization problem had at least quasi-linear time complexity, here the first algorithm with linear time complexity and constant space complexity is proposed. The key for this is the mathematically rigorous derivation of a characterization of the projection's result based on a soft-shrinkage function. This theory is applied in an original algorithm called Easy Dictionary Learning (EZDL), which learns dictionaries with a simple and fast-to-compute Hebbian-like learning rule. The new algorithm is efficient, expressive and particularly simple to implement. It is demonstrated that despite its simplicity, the proposed learning algorithm is able to generate a rich variety of dictionaries, in particular a topographic organization of atoms or separable atoms. Further, the dictionaries are as expressive as those of benchmark learning algorithms in terms of the reproduction quality on entire images, and result in an equivalent denoising performance. EZDL learns approximately 30 % faster than the already very efficient Online Dictionary Learning algorithm, and is therefore eligible for rapid data set analysis and problems with vast quantities of learning samples.

##### Abstract (translated by Google)
学习字典适合稀疏编码，而不是使用工程基地已被证明有效的各种图像处理任务。本文研究了对图像数据字典的优化，其中对于平滑的，归一化的稀疏度量，表示被强制显式地稀疏。这涉及到在稀疏度量的水平集上的欧几里得投影的计算。虽然以前的算法至少具有准线性时间复杂度，但是这里提出了具有线性时间复杂度和恒定空间复杂度的第一种算法。关键是在数学上严格推导出基于软收缩函数的投影结果的表征。这个理论被应用在一个叫做Easy Dictionary Learning（EZDL）的原始算法中，该算法通过一个简单而快速的Hebbian-like学习规则来学习字典。新算法效率高，表现力强，实现起来特别简单。已经证明，尽管简单，所提出的学习算法能够生成丰富多样的字典，特别是原子或可分离原子的地形组织。此外，字典在整个图像的再现质量方面与基准学习算法一样具有表现力，并且导致等同的去噪性能。 EZDL的学习速度比已有的在线词典学习算法快大约30％，因此有资格进行快速的数据集分析以及大量学习样本的问题。

##### URL
[https://arxiv.org/abs/1604.04767](https://arxiv.org/abs/1604.04767)

##### PDF
[https://arxiv.org/pdf/1604.04767](https://arxiv.org/pdf/1604.04767)

