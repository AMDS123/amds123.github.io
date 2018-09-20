---
layout: post
title: "Linear SLAM: Linearising the SLAM Problems using Submap Joining"
date: 2018-09-18 23:57:34
categories: arXiv_RO
tags: arXiv_RO Optimization SLAM
author: Liang Zhao, Shoudong Huang, Gamini Dissanayake
mathjax: true
---

* content
{:toc}

##### Abstract
The main contribution of this paper is a new submap joining based approach for solving large-scale Simultaneous Localization and Mapping (SLAM) problems. Each local submap is independently built using the local information through solving a small-scale SLAM; the joining of submaps mainly involves solving linear least squares and performing nonlinear coordinate transformations. Through approximating the local submap information as the state estimate and its corresponding information matrix, judiciously selecting the submap coordinate frames, and approximating the joining of a large number of submaps by joining only two maps at a time, either sequentially or in a more efficient Divide and Conquer manner, the nonlinear optimization process involved in most of the existing submap joining approaches is avoided. Thus the proposed submap joining algorithm does not require initial guess or iterations since linear least squares problems have closed-form solutions. The proposed Linear SLAM technique is applicable to feature-based SLAM, pose graph SLAM and D-SLAM, in both two and three dimensions, and does not require any assumption on the character of the covariance matrices. Simulations and experiments are performed to evaluate the proposed Linear SLAM algorithm. Results using publicly available datasets in 2D and 3D show that Linear SLAM produces results that are very close to the best solutions that can be obtained using full nonlinear optimization algorithm started from an accurate initial guess. The C/C++ and MATLAB source codes of Linear SLAM are available on OpenSLAM.

##### Abstract (translated by Google)
本文的主要贡献是一种新的基于子图连接的方法，用于解决大规模同时定位和映射（SLAM）问题。通过求解小规模SLAM，使用本地信息独立构建每个本地子图;子图的连接主要涉及求解线性最小二乘和执行非线性坐标变换。通过将局部子图信息近似为状态估计及其对应的信息矩阵，明智地选择子图坐标帧，并通过一次仅连接两个图来近似加入大量子图，顺序地或者在更有效的分割中和Conquer方式，避免了大多数现有子图连接方法中涉及的非线性优化过程。因此，所提出的子图连接算法不需要初始猜测或迭代，因为线性最小二乘问题具有封闭形式的解。所提出的线性SLAM技术适用于基于特征的SLAM，姿势图SLAM和D-SLAM，在二维和三维中，并且不需要对协方差矩阵的特征进行任何假设。进行模拟和实验以评估所提出的线性SLAM算法。使用2D和3D中公开可用的数据集的结果表明，线性SLAM产生的结果非常接近可以使用从准确的初始猜测开始的完全非线性优化算法获得的最佳解决方案。线性SLAM的C / C ++和MATLAB源代码可在OpenSLAM上获得。

##### URL
[http://arxiv.org/abs/1809.06967](http://arxiv.org/abs/1809.06967)

##### PDF
[http://arxiv.org/pdf/1809.06967](http://arxiv.org/pdf/1809.06967)

