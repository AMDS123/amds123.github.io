---
layout: post
title: "Reduced Basis Decomposition: a Certified and Fast Lossy Data Compression Algorithm"
date: 2015-03-19 21:10:57
categories: arXiv_CV
tags: arXiv_CV
author: Yanlai Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Dimension reduction is often needed in the area of data mining. The goal of these methods is to map the given high-dimensional data into a low-dimensional space preserving certain properties of the initial data. There are two kinds of techniques for this purpose. The first, projective methods, builds an explicit linear projection from the high-dimensional space to the low-dimensional one. On the other hand, the nonlinear methods utilizes nonlinear and implicit mapping between the two spaces. In both cases, the methods considered in literature have usually relied on computationally very intensive matrix factorizations, frequently the Singular Value Decomposition (SVD). The computational burden of SVD quickly renders these dimension reduction methods infeasible thanks to the ever-increasing sizes of the practical datasets. In this paper, we present a new decomposition strategy, Reduced Basis Decomposition (RBD), which is inspired by the Reduced Basis Method (RBM). Given $X$ the high-dimensional data, the method approximates it by $Y \, T (\approx X)$ with $Y$ being the low-dimensional surrogate and $T$ the transformation matrix. $Y$ is obtained through a greedy algorithm thus extremely efficient. In fact, it is significantly faster than SVD with comparable accuracy. $T$ can be computed on the fly. Moreover, unlike many compression algorithms, it easily finds the mapping for an arbitrary ``out-of-sample'' vector and it comes with an ``error indicator'' certifying the accuracy of the compression. Numerical results are shown validating these claims.

##### Abstract (translated by Google)
在数据挖掘领域经常需要降维。这些方法的目标是将给定的高维数据映射到保持初始数据的某些属性的低维空间。有两种技术用于这个目的。首先，投影方法建立了从高维空间到低维空间的显式线性投影。另一方面，非线性方法利用两个空间之间的非线性和隐式映射。在这两种情况下，文献中考虑的方法通常都依赖于计算量非常大的矩阵分解，通常是奇异值分解（SVD）。由于实际数据集的大小不断增加，SVD的计算负担很快使这些降维方法变得不可行。在本文中，我们提出了一个新的分解策略，即基于Reduce Basis方法（RBM）的Reduce Basis Decomposition（RBD）。给定$ X $的高维数据，该方法近似于$ Y \，T（\ approx X）$，其中$ Y $是低维替代变量，$ T $是变换矩阵。 $ Y $是通过贪婪算法获得的，因此非常有效。事实上，它比SVD快得多，具有相当的准确性。 $ T $可以即时计算。而且，与许多压缩算法不同的是，它很容易找到任意“样本外”向量的映射，并带有一个证明压缩准确性的“错误指示符”。显示的数值结果验证了这些声明。

##### URL
[https://arxiv.org/abs/1503.05947](https://arxiv.org/abs/1503.05947)

##### PDF
[https://arxiv.org/pdf/1503.05947](https://arxiv.org/pdf/1503.05947)

