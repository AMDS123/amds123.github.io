---
layout: post
title: "Fitting Generalized Essential Matrices from Generic 6x6 Matrices and its Applications"
date: 2017-09-19 10:10:09
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation Optimization
author: João R. Cardoso, Pedro Miraldo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of finding the closest generalized essential matrix from a given 6x6 matrix, with respect to the Frobenius norm. To the best of our knowledge, this nonlinear constrained optimization problem has not been addressed in the literature yet. Although it can be solved directly, it involves a large amount of 33 constraints, and any optimization method to solve it will require much computational time. Then, we start by converting the original problem into a new one, involving only orthogonal constraints, and propose an efficient algorithm of steepest descent-type to find the goal solution. To test the algorithm, we evaluate with both synthetic and real data. From the results with synthetic data, we conclude that the proposed method is much faster than applying general optimization techniques to the original problem with 33 constraints. To conclude and to further motivate the relevance of our method, we develop an efficient and robust algorithm for estimation of the general relative pose problem, which will be compared with the state-of-the-art techniques. It is shown, in particular, that some existing approaches to solving the relative pose estimation problem can be considerably improved, if combined with our method for estimating the closest generalized essential matrix. Real data to validate the algorithm is used as well.

##### Abstract (translated by Google)
本文讨论了在Frobenius范数方面，从给定的6x6矩阵中找出最接近的广义本质矩阵的问题。就我们所知，这种非线性约束优化问题还没有在文献中得到解决。虽然它可以直接解决，但它涉及到大量的约束条件，任何解决这个问题的优化方法都需要大量的计算时间。然后，我们开始把原来的问题转换成一个新的问题，只涉及正交约束，并提出一个有效的最速下降型算法来寻找目标解。为了测试算法，我们用合成和真实数据进行评估。从合成数据的结果来看，我们得出的结论是，所提出的方法比使用一般优化技术对具有33个约束的原始问题要快得多。总结和进一步激励我们的方法的相关性，我们开发了一个有效的和稳健的算法估计的一般相对位姿问题，这将与最先进的技术进行比较。特别是，如果结合我们的估计最接近的广义基本矩阵的方法，特别显示了解决相对姿态估计问题的一些现有方法可以显着改善。真实的数据来验证算法也被使用。

##### URL
[https://arxiv.org/abs/1709.06328](https://arxiv.org/abs/1709.06328)

##### PDF
[https://arxiv.org/pdf/1709.06328](https://arxiv.org/pdf/1709.06328)

