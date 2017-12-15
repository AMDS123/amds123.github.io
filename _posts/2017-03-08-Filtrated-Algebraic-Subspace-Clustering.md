---
layout: post
title: "Filtrated Algebraic Subspace Clustering"
date: 2017-03-08 18:49:41
categories: arXiv_CV
tags: arXiv_CV
author: Manolis C. Tsakiris, Rene Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
Subspace clustering is the problem of clustering data that lie close to a union of linear subspaces. In the abstract form of the problem, where no noise or other corruptions are present, the data are assumed to lie in general position inside the algebraic variety of a union of subspaces, and the objective is to decompose the variety into its constituent subspaces. Prior algebraic-geometric approaches to this problem require the subspaces to be of equal dimension, or the number of subspaces to be known. Subspaces of arbitrary dimensions can still be recovered in closed form, in terms of all homogeneous polynomials of degree $m$ that vanish on their union, when an upper bound m on the number of the subspaces is given. In this paper, we propose an alternative, provably correct, algorithm for addressing a union of at most $m$ arbitrary-dimensional subspaces, based on the idea of descending filtrations of subspace arrangements. Our algorithm uses the gradient of a vanishing polynomial at a point in the variety to find a hyperplane containing the subspace S passing through that point. By intersecting the variety with this hyperplane, we obtain a subvariety that contains S, and recursively applying the procedure until no non-trivial vanishing polynomial exists, our algorithm eventually identifies S. By repeating this procedure for other points, our algorithm eventually identifies all the subspaces by returning a basis for their orthogonal complement. Finally, we develop a variant of the abstract algorithm, suitable for computations with noisy data. We show by experiments on synthetic and real data that the proposed algorithm outperforms state-of-the-art methods on several occasions, thus demonstrating the merit of the idea of filtrations.

##### Abstract (translated by Google)
子空间聚类是对靠近线性子空间联合的数据进行聚类的问题。在问题的抽象形式中，在没有噪声或其他腐败存在的情况下，数据被假定位于子空间联合的代数变种内的一般位置，目标是将变种分解为其组成子空间。对于这个问题的现有代数几何方法要求子空间具有相等的维数，或者子空间的数量是已知的。任意维数的子空间仍然可以以关联形式恢复，当给定子空间数的上界m时，就所有在其联合中消失的度为$ m $的齐次多项式而言。在本文中，我们提出了一种替代的，可证明是正确的算法，用于处理最多$ m $任意维子空间的联合，这是基于子空间排列下降过滤的思想。我们的算法使用消失多项式的梯度在变种中的一个点处找到包含通过该点的子空间S的超平面。通过把这个变种与这个超平面相交，我们得到一个包含S的子变量，并递归地应用这个过程直到没有非平凡的消失多项式存在，我们的算法最终识别S.通过对其他点重复这个过程，我们的算法最终识别所有的子空间通过返回正交补的基础。最后，我们开发了一个抽象算法的变体，适合于有噪声数据的计算。我们通过对合成和实际数据的实验表明，所提出的算法多次胜过最先进的方法，从而证明了过滤思想的优点。

##### URL
[https://arxiv.org/abs/1506.06289](https://arxiv.org/abs/1506.06289)

##### PDF
[https://arxiv.org/pdf/1506.06289](https://arxiv.org/pdf/1506.06289)

