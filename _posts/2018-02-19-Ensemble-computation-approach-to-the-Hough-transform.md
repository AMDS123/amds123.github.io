---
layout: post
title: "Ensemble computation approach to the Hough transform"
date: 2018-02-19 13:28:18
categories: arXiv_CV
tags: arXiv_CV
author: Timur M. Khanipov
mathjax: true
---

* content
{:toc}

##### Abstract
It is demonstrated that the classical Hough transform with shift-elevation parametrization of digital straight lines has additive complexity of at most $\mathcal{O}(n^3 / \log n)$ on a $n\times n$ image. The proof is constructive and uses ensemble computation approach to build summation circuits. The proposed method has similarities with the fast Hough transform (FHT) and may be considered a form of the "divide and conquer" technique. It is based on the fact that lines with close slopes can be decomposed into common components, allowing generalization for other pattern families. When applied to FHT patterns, the algorithm yields exactly the $\Theta(n^2\log n)$ FHT asymptotics which might suggest that the actual classical Hough transform circuits could smaller size than $\Theta(n^3/ \log n)$.

##### Abstract (translated by Google)
证明了具有数字直线的移位高度参数化的经典霍夫变换在$ n \ times n $图像上具有至多$ \ mathcal {O}（n ^ 3 / \ log n）$的附加复杂度。证明是建设性的，并使用集成计算方法来构建求和电路。所提出的方法与快速霍夫变换（FHT）具有相似性，并且可以被认为是“分而治之”技术的一种形式。它基于这样一个事实，即具有接近斜率的线可以分解为常见组件，从而可以推广到其他模式系列。当应用于FHT模式时，该算法恰好产生$ \ Theta（n ^ 2 \ log n）$ FHT渐近线，这可能表明实际的经典Hough变换电路可能比$ \ Theta（n ^ 3 / \ log n ）$。

##### URL
[http://arxiv.org/abs/1802.06619](http://arxiv.org/abs/1802.06619)

##### PDF
[http://arxiv.org/pdf/1802.06619](http://arxiv.org/pdf/1802.06619)

