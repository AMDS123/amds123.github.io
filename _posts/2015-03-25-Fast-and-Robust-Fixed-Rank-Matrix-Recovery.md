---
layout: post
title: "Fast and Robust Fixed-Rank Matrix Recovery"
date: 2015-03-25 09:26:04
categories: arXiv_CV
tags: arXiv_CV Sparse
author: German Ros, Julio Guerrero
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of efficient sparse fixed-rank (S-FR) matrix decomposition, i.e., splitting a corrupted matrix $M$ into an uncorrupted matrix $L$ of rank $r$ and a sparse matrix of outliers $S$. Fixed-rank constraints are usually imposed by the physical restrictions of the system under study. Here we propose a method to perform accurate and very efficient S-FR decomposition that is more suitable for large-scale problems than existing approaches. Our method is a grateful combination of geometrical and algebraical techniques, which avoids the bottleneck caused by the Truncated SVD (TSVD). Instead, a polar factorization is used to exploit the manifold structure of fixed-rank problems as the product of two Stiefel and an SPD manifold, leading to a better convergence and stability. Then, closed-form projectors help to speed up each iteration of the method. We introduce a novel and fast projector for the $\text{SPD}$ manifold and a proof of its validity. Further acceleration is achieved using a Nystrom scheme. Extensive experiments with synthetic and real data in the context of robust photometric stereo and spectral clustering show that our proposals outperform the state of the art.

##### Abstract (translated by Google)
我们解决了有效的稀疏固定秩（S-FR）矩阵分解的问题，即将损坏的矩阵$ M $分解成秩为$ r $的未被破坏的矩阵$ L $和离群值$ S $的稀疏矩阵。固定等级约束通常是由所研究的系统的物理限制来强加的。在这里我们提出一种方法来执行精确和非常有效的S-FR分解，比现有方法更适合于大规模问题。我们的方法是几何和代数技术的一种感谢结合，避免了截断奇异值分解（TSVD）造成的瓶颈。相反，使用极性因子分解方法来利用固定秩问题的流形结构作为两个Stiefel和SPD流形的乘积，从而获得更好的收敛性和稳定性。然后，封闭式投影机帮助加速该方法的每次迭代。我们为$ \ text {SPD} $流形引入了一种新颖且快速的投影仪，并证明了它的有效性。使用Nystrom方案进一步加速。在强大的光度立体和光谱聚类背景下，利用合成和实际数据进行的大量实验表明，我们的建议超越了现有技术水平。

##### URL
[https://arxiv.org/abs/1503.03004](https://arxiv.org/abs/1503.03004)

##### PDF
[https://arxiv.org/pdf/1503.03004](https://arxiv.org/pdf/1503.03004)

