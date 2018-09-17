---
layout: post
title: "Revisiting Random Binning Features: Fast Convergence and Strong Parallelizability"
date: 2018-09-14 04:06:35
categories: arXiv_AI
tags: arXiv_AI Attention Optimization
author: Lingfei Wu, Ian E.H. Yen, Jie Chen, Rui Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Kernel method has been developed as one of the standard approaches for nonlinear learning, which however, does not scale to large data set due to its quadratic complexity in the number of samples. A number of kernel approximation methods have thus been proposed in the recent years, among which the random features method gains much popularity due to its simplicity and direct reduction of nonlinear problem to a linear one. The Random Binning (RB) feature, proposed in the first random-feature paper \cite{rahimi2007random}, has drawn much less attention than the Random Fourier (RF) feature. In this work, we observe that the RB features, with right choice of optimization solver, could be orders-of-magnitude more efficient than other random features and kernel approximation methods under the same requirement of accuracy. We thus propose the first analysis of RB from the perspective of optimization, which by interpreting RB as a Randomized Block Coordinate Descent in the infinite-dimensional space, gives a faster convergence rate compared to that of other random features. In particular, we show that by drawing $R$ random grids with at least $\kappa$ number of non-empty bins per grid in expectation, RB method achieves a convergence rate of $O(1/(\kappa R))$, which not only sharpens its $O(1/\sqrt{R})$ rate from Monte Carlo analysis, but also shows a $\kappa$ times speedup over other random features under the same analysis framework. In addition, we demonstrate another advantage of RB in the L1-regularized setting, where unlike other random features, a RB-based Coordinate Descent solver can be parallelized with guaranteed speedup proportional to $\kappa$. Our extensive experiments demonstrate the superior performance of the RB features over other random features and kernel approximation methods. Our code and data is available at { \url{https://github.com/teddylfwu/RandomBinning}}.

##### Abstract (translated by Google)
核方法已被开发为非线性学习的标准方法之一，然而由于其样本数量的二次复杂性，其不能扩展到大数据集。近年来已经提出了许多核近似方法，其中随机特征方法由于其简单性和非线性问题直接减少为线性问题而获得了很大的普及。在第一个随机特征论文\引用{rahimi2007random}中提出的随机分箱（RB）特征比随机傅立叶（RF）特征引起的关注要少得多。在这项工作中，我们观察到RB功能，正确选择优化求解器，在相同的精度要求下，可以比其他随机特征和核近似方法更有效。因此，我们从优化的角度提出RB的第一次分析，通过将RB解释为无限维空间中的随机块坐标下降，与其他随机特征相比，提供了更快的收敛速度。特别是，我们通过绘制$ R $随机网格，每个网格的预期值至少为$ \ kappa $非空箱数，RB方法实现了收敛率$ O（1 /（\ kappa R））$ ，它不仅可以从蒙特卡罗分析中提高其$ O（1 / \ sqrt {R}）美元汇率，而且还可以显示相同分析框架下其他随机功能的$ \ kappa $倍速。此外，我们在L1正则化设置中展示了RB的另一个优势，与其他随机特征不同，基于RB的坐标下降求解器可以并行化，保证加速与$ \ kappa $成比例。我们的大量实验证明了RB特性优于其他随机特征和核近似方法的优越性能。我们的代码和数据可在{\ url {https://github.com/teddylfwu/RandomBinning}}上找到。

##### URL
[http://arxiv.org/abs/1809.05247](http://arxiv.org/abs/1809.05247)

##### PDF
[http://arxiv.org/pdf/1809.05247](http://arxiv.org/pdf/1809.05247)

