---
layout: post
title: "Fast initial guess estimation for digital image correlation"
date: 2017-10-12 04:20:00
categories: arXiv_CV
tags: arXiv_CV Optimization Quantitative Relation
author: Peihan Tu
mathjax: true
---

* content
{:toc}

##### Abstract
Digital image correlation (DIC) is a widely used optical metrology for quantitative deformation measurement due to its non-contact, low-cost, highly precise feature. DIC relies on nonlinear optimization algorithm. Thus it is quite important to efficiently obtain a reliable initial guess. The most widely used method for obtaining initial guess is reliability-guided digital image correlation (RG-DIC) method, which is reliable but path-dependent. This path-dependent method limits the further improvement of computation speed of DIC using parallel computing technology, and error of calculation may be spread out along the calculation path. Therefore, a reliable and path-independent algorithm which is able to provide reliable initial guess is desirable to reach full potential of the ability of parallel computing. In this paper, an algorithm used for initial guess estimation is proposed. Numerical and real experiments show that the proposed algorithm, adaptive incremental dissimilarity approximations algorithm (A-IDA), has the following characteristics: 1) Compared with inverse compositional Gauss-Newton (IC-GN) sub-pixel registration algorithm, the computational time required by A-IDA algorithm is negligible, especially when subset size is relatively large; 2) the efficiency of A-IDA algorithm is less influenced by search range; 3) the efficiency is less influenced by subset size; 4) it is easy to select the threshold for the proposed algorithm.

##### Abstract (translated by Google)
数字图像相关（DIC）是一种广泛用于定量变形测量的光学计量学，由于其非接触，低成本，高度精确的特点。 DIC依赖于非线性优化算法。因此，有效获得可靠的初始猜测是非常重要的。获得初始猜测的最广泛使用的方法是可靠性引导的数字图像相关（RG-DIC）方法，其是可靠的但是路径相关的。这种依赖于路径的方法限制了使用并行计算技术进一步提高DIC的计算速度，计算误差可能沿着计算路径分布。因此，能够提供可靠的初始猜测的可靠且路径独立的算法是可取的，以充分发挥并行计算能力。本文提出了一种用于初始猜测估计的算法。数值实验表明，所提出的自适应增量相异近似算法（A-IDA）具有以下特点：1）与逆成分高斯 - 牛顿（IC-GN）亚像素配准算法相比，所需的计算时间通过A-IDA算法可以忽略不计，特别是当子集大小相对较大时; 2）A-IDA算法的效率受搜索范围的影响较小; 3）效率受子集大小的影响较小; 4）提出的算法很容易选择阈值。

##### URL
[https://arxiv.org/abs/1710.04359](https://arxiv.org/abs/1710.04359)

##### PDF
[https://arxiv.org/pdf/1710.04359](https://arxiv.org/pdf/1710.04359)

