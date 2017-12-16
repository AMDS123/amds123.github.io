---
layout: post
title: "Sliced Wasserstein Distance for Learning Gaussian Mixture Models"
date: 2017-11-16 02:05:11
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent Relation
author: Soheil Kolouri, Gustavo K. Rohde, Heiko Hoffmann
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian mixture models (GMM) are powerful parametric tools with many applications in machine learning and computer vision. Expectation maximization (EM) is the most popular algorithm for estimating the GMM parameters. However, EM guarantees only convergence to a stationary point of the log-likelihood function, which could be arbitrarily worse than the optimal solution. Inspired by the relationship between the negative log-likelihood function and the Kullback-Leibler (KL) divergence, we propose an alternative formulation for estimating the GMM parameters using the sliced Wasserstein distance, which gives rise to a new algorithm. Specifically, we propose minimizing the sliced-Wasserstein distance between the mixture model and the data distribution with respect to the GMM parameters. In contrast to the KL-divergence, the energy landscape for the sliced-Wasserstein distance is more well-behaved and therefore more suitable for a stochastic gradient descent scheme to obtain the optimal GMM parameters. We show that our formulation results in parameter estimates that are more robust to random initializations and demonstrate that it can estimate high-dimensional data distributions more faithfully than the EM algorithm.

##### Abstract (translated by Google)
高斯混合模型（GMM）是强大的参数化工具，在机器学习和计算机视觉领域有许多应用。期望最大化（EM）是估计GMM参数最流行的算法。然而，EM保证只能收敛到对数似然函数的一个平稳点，这可能比最优解更差。受负对数似然函数和Kullback-Leibler（KL）散度之间的关系的启发，我们提出了一种用切片Wasserstein距离估计GMM参数的替代公式，从而产生了一种新的算法。具体而言，我们提出了最小化混合模型和数据分布之间关于GMM参数的切片Wasserstein距离。与KL散度相比，切片Wasserstein距离的能量景观更加良好，因此更适合于随机梯度下降方案来获得最优的GMM参数。我们表明，我们的公式的结果参数估计是更强大的随机初始化，并表明它可以比EM算法更忠实地估计高维数据分布。

##### URL
[https://arxiv.org/abs/1711.05376](https://arxiv.org/abs/1711.05376)

##### PDF
[https://arxiv.org/pdf/1711.05376](https://arxiv.org/pdf/1711.05376)

