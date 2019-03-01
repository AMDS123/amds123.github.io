---
layout: post
title: "Private Center Points and Learning of Halfspaces"
date: 2019-02-27 19:06:12
categories: arXiv_AI
tags: arXiv_AI Relation
author: Amos Beimel, Shay Moran, Kobbi Nissim, Uri Stemmer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a private learner for halfspaces over an arbitrary finite domain $X\subset \mathbb{R}^d$ with sample complexity $mathrm{poly}(d,2^{\log^*|X|})$. The building block for this learner is a differentially private algorithm for locating an approximate center point of $m&gt;\mathrm{poly}(d,2^{\log^*|X|})$ points -- a high dimensional generalization of the median function. Our construction establishes a relationship between these two problems that is reminiscent of the relation between the median and learning one-dimensional thresholds [Bun et al.\ FOCS '15]. This relationship suggests that the problem of privately locating a center point may have further applications in the design of differentially private algorithms. 
 We also provide a lower bound on the sample complexity for privately finding a point in the convex hull. For approximate differential privacy, we show a lower bound of $m=\Omega(d+\log^*|X|)$, whereas for pure differential privacy $m=\Omega(d\log|X|)$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10731](http://arxiv.org/abs/1902.10731)

##### PDF
[http://arxiv.org/pdf/1902.10731](http://arxiv.org/pdf/1902.10731)

