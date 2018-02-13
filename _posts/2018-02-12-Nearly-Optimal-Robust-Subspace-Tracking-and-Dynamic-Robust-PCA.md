---
layout: post
title: "Nearly Optimal Robust Subspace Tracking and Dynamic Robust PCA"
date: 2018-02-12 00:29:16
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking
author: Praneeth Narayanamurthy, Namrata Vaswani
mathjax: true
---

* content
{:toc}

##### Abstract
We study the robust subspace tracking (RST) problem and obtain one of the first provable guarantees for it. The goal of RST is to track data that lies in a slowly changing low-dimensional subspace, and the subspaces themselves, while being robust to corruption by (often large magnitude) sparse outliers. It can be simply interpreted as a dynamic (time-varying) extension of robust PCA, with the minor difference that RST also requires an online algorithm (short tracking delay). We propose an algorithm called NORST (nearly optimal RST) and prove that it solves both RST and dynamic robust PCA under weakened versions of standard RPCA assumptions, slow subspace change, and two simple extra assumptions (a lower bound on outlier magnitudes, and independence of the columns of the low-rank matrix). 
 Our guarantee shows that NORST enjoys a near optimal tracking delay of $O(r \log n \log(1/\varepsilon))$. Its required delay between subspace change times is the same, and its memory complexity is $n$ times this value. Here $n$ is the ambient space dimension and $r$ is the dimension of the changing subspaces in which the true data lies. Thus both these are also nearly optimal. Finally, our guarantee also shows that NORST has the best outlier tolerance compared with all previous RPCA or RST methods, both theoretically and empirically (including for real videos), without requiring any model on outlier support sets.

##### Abstract (translated by Google)
我们研究鲁棒子空间跟踪（RST）问题并获得其中的第一个可证明的保证。 RST的目标是跟踪位于缓慢变化的低维子空间中的数据以及子空间本身，同时通过（通常是大量的）稀疏异常值对腐败强大。它可以简单地解释为鲁棒PCA的动态（时变）扩展，其细微差别在于RST也需要在线算法（短的跟踪延迟）。我们提出了一种名为NORST（近似最优RST）的算法，并证明它在标准RPCA假设的减弱版本，缓慢的子空间变化和两个简单​​的额外假设（对异常值的下限和独立性的独立性）下解决了RST和动态鲁棒PCA低秩矩阵的列）。
 我们的保证显示NORST享有$ O（r \ log n \ log（1 / \ varepsilon））$的最佳跟踪延迟。它在子空间变化时间之间所需的延迟是相同的，其存储器复杂度是该值的$ n $倍。这里$ n $是环境空间维度，$ r $是真实数据所在的变化子空间的维度。因此这两者也几乎是最佳的。最后，我们的保证还表明，与理论上和经验上（包括实际视频）相比，NORST具有与以前的所有RPCA或RST方法相比最佳的异常值容忍度，而不需要任何关于异常值支持集的模型。

##### URL
[http://arxiv.org/abs/1712.06061](http://arxiv.org/abs/1712.06061)

##### PDF
[http://arxiv.org/pdf/1712.06061](http://arxiv.org/pdf/1712.06061)

