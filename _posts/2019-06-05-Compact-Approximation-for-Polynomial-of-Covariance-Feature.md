---
layout: post
title: "Compact Approximation for Polynomial of Covariance Feature"
date: 2019-06-05 06:46:58
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Yusuke Mukuta, Tatsuaki Machida, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Covariance pooling is a feature pooling method with good classification accuracy. Because covariance features consist of second-order statistics, the scale of the feature elements are varied. Therefore, normalizing covariance features using a matrix square root affects the performance improvement. When pooling methods are applied to local features extracted from CNN models, the accuracy increases when the pooling function is back-propagatable and the feature-extraction model is learned in an end-to-end manner. Recently, the iterative polynomial approximation method for the matrix square root of a covariance feature was proposed, and resulted in a faster and more stable training than the methods based on singular-value decomposition. In this paper, we propose an extension of compact bilinear pooling, which is a compact approximation of the standard covariance feature, to the polynomials of the covariance feature. Subsequently, we apply the proposed approximation to the polynomial corresponding to the matrix square root to obtain a compact approximation for the square root of the covariance feature. Our method approximates a higher-dimensional polynomial of a covariance by the weighted sum of the approximate features corresponding to a pair of local features based on the similarity of the local features. We apply our method for standard fine-grained image recognition datasets and demonstrate that the proposed method shows comparable accuracy with fewer dimensions than the original feature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01851](http://arxiv.org/abs/1906.01851)

##### PDF
[http://arxiv.org/pdf/1906.01851](http://arxiv.org/pdf/1906.01851)

