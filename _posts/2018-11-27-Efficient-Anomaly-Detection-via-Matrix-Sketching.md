---
layout: post
title: "Efficient Anomaly Detection via Matrix Sketching"
date: 2018-11-27 16:46:19
categories: arXiv_AI
tags: arXiv_AI Detection
author: Vatsal Sharan, Parikshit Gopalan, Udi Wieder
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of finding anomalies in high-dimensional data using popular PCA based anomaly scores. The naive algorithms for computing these scores explicitly compute the PCA of the covariance matrix which uses space quadratic in the dimensionality of the data. We give the first streaming algorithms that use space that is linear or sublinear in the dimension. We prove general results showing that \emph{any} sketch of a matrix that satisfies a certain operator norm guarantee can be used to approximate these scores. We instantiate these results with powerful matrix sketching techniques such as Frequent Directions and random projections to derive efficient and practical algorithms for these problems, which we validate over real-world data sets. Our main technical contribution is to prove matrix perturbation inequalities for operators arising in the computation of these measures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.03065](http://arxiv.org/abs/1804.03065)

##### PDF
[http://arxiv.org/pdf/1804.03065](http://arxiv.org/pdf/1804.03065)

