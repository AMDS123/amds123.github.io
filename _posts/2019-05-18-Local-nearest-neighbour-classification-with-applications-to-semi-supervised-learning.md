---
layout: post
title: "Local nearest neighbour classification with applications to semi-supervised learning"
date: 2019-05-18 10:49:46
categories: arXiv_CV
tags: arXiv_CV Classification
author: Timothy I. Cannings, Thomas B. Berrett, Richard J. Samworth
mathjax: true
---

* content
{:toc}

##### Abstract
We derive a new asymptotic expansion for the global excess risk of a local-$k$-nearest neighbour classifier, where the choice of $k$ may depend upon the test point. This expansion elucidates conditions under which the dominant contribution to the excess risk comes from the decision boundary of the optimal Bayes classifier, but we also show that if these conditions are not satisfied, then the dominant contribution may arise from the tails of the marginal distribution of the features. Moreover, we prove that, provided the $d$-dimensional marginal distribution of the features has a finite $\rho$th moment for some $\rho &gt; 4$ (as well as other regularity conditions), a local choice of $k$ can yield a rate of convergence of the excess risk of $O(n^{-4/(d+4)})$, where $n$ is the sample size, whereas for the standard $k$-nearest neighbour classifier, our theory would require $d \geq 5$ and $\rho &gt; 4d/(d-4)$ finite moments to achieve this rate. These results motivate a new $k$-nearest neighbour classifier for semi-supervised learning problems, where the unlabelled data are used to obtain an estimate of the marginal feature density, and fewer neighbours are used for classification when this density estimate is small. Our worst-case rates are complemented by a minimax lower bound, which reveals that the local, semi-supervised $k$-nearest neighbour classifier attains the minimax optimal rate over our classes for the excess risk, up to a subpolynomial factor in $n$. These theoretical improvements over the standard $k$-nearest neighbour classifier are also illustrated through a simulation study.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1704.00642](http://arxiv.org/abs/1704.00642)

##### PDF
[http://arxiv.org/pdf/1704.00642](http://arxiv.org/pdf/1704.00642)

