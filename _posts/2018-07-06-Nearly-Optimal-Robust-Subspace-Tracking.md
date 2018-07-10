---
layout: post
title: "Nearly Optimal Robust Subspace Tracking"
date: 2018-07-06 17:41:33
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking
author: Praneeth Narayanamurthy, Namrata Vaswani
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we study the robust subspace tracking (RST) problem and obtain one of the first two provable guarantees for it. The goal of RST is to track sequentially arriving data vectors that lie in a slowly changing low-dimensional subspace, while being robust to corruption by additive sparse outliers. It can also be interpreted as a dynamic (time-varying) extension of robust PCA (RPCA), with the minor difference that RST also requires a short tracking delay. We develop a recursive projected compressive sensing algorithm that we call Nearly Optimal RST via ReProCS (ReProCS-NORST) because its tracking delay is nearly optimal. We prove that NORST solves both the RST and the dynamic RPCA problems under weakened standard RPCA assumptions, two simple extra assumptions (slow subspace change and most outlier magnitudes lower bounded), and a few minor assumptions. 
 Our guarantee shows that NORST enjoys a near optimal tracking delay of $O(r \log n \log(1/\epsilon))$. Its required delay between subspace change times is the same, and its memory complexity is $n$ times this value. Thus both these are also nearly optimal. Here $n$ is the ambient space dimension, $r$ is the subspaces' dimension, and $\epsilon$ is the tracking accuracy. NORST also has the best outlier tolerance compared with all previous RPCA or RST methods, both theoretically and empirically (including for real videos), without requiring any model on how the outlier support is generated. This is possible because of the extra assumptions it uses.

##### Abstract (translated by Google)
在这项工作中，我们研究了鲁棒子空间跟踪（RST）问题，并获得了前两个可证明的保证之一。 RST的目标是跟踪位于缓慢变化的低维子空间中的顺序到达的数据向量，同时通过加性稀疏异常值对损坏具有鲁棒性。它也可以被解释为鲁棒PCA（RPCA）的动态（时变）扩展，RST也需要较短的跟踪延迟。我们开发了一种递归投影压缩感知算法，我们通过ReProCS（ReProCS-NORST）将其称为近似最优RST，因为它的跟踪延迟几乎是最优的。我们证明了NORST在弱化的标准RPCA假设下，两个简单的额外假设（缓慢的子空间变化和大多数异常值下限）和一些小的假设下解决了RST和动态RPCA问题。
 我们的保证表明，NORST的追踪延迟接近$ O（r \ log n \ log（1 / \ epsilon））$。子空间更改时间之间所需的延迟是相同的，其内存复杂度是此值的$ n $倍。因此这两者也几乎是最佳的。这里$ n $是环境空间维度，$ r $是子空间的维度，$ \ epsilon $是跟踪精度。与所有以前的RPCA或RST方法相比，NORST在理论上和经验上（包括真实视频）都具有最佳的异常值容限，而不需要任何关于如何生成异常值支持的模型。这是可能的，因为它使用了额外的假设。

##### URL
[http://arxiv.org/abs/1712.06061](http://arxiv.org/abs/1712.06061)

##### PDF
[http://arxiv.org/pdf/1712.06061](http://arxiv.org/pdf/1712.06061)

