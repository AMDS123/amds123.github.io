---
layout: post
title: "Fast and Globally Optimal Rigid Registration of 3D Point Sets by Transformation Decomposition"
date: 2018-12-29 07:46:48
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Xuechen Li, Yinlong Liu, Yiru Wang, Chen Wang, Manning Wang, Zhijian Song
mathjax: true
---

* content
{:toc}

##### Abstract
The rigid registration of two 3D point sets is a fundamental problem in computer vision. The current trend is to solve this problem globally using the BnB optimization framework. However, the existing global methods are slow for two main reasons: the computational complexity of BnB is exponential to the problem dimensionality (which is six for 3D rigid registration), and the bound evaluation used in BnB is inefficient. In this paper, we propose two techniques to address these problems. First, we introduce the idea of translation invariant vectors, which allows us to decompose the search of a 6D rigid transformation into a search of 3D rotation followed by a search of 3D translation, each of which is solved by a separate BnB algorithm. This transformation decomposition reduces the problem dimensionality of BnB algorithms and substantially improves its efficiency. Then, we propose a new data structure, named 3D Integral Volume, to accelerate the bound evaluation in both BnB algorithms. By combining these two techniques, we implement an efficient algorithm for rigid registration of 3D point sets. Extensive experiments on both synthetic and real data show that the proposed algorithm is three orders of magnitude faster than the existing state-of-the-art global methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11307](http://arxiv.org/abs/1812.11307)

##### PDF
[http://arxiv.org/pdf/1812.11307](http://arxiv.org/pdf/1812.11307)

