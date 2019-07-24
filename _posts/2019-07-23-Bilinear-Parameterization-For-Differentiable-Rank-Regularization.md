---
layout: post
title: "Bilinear Parameterization For Differentiable Rank-Regularization"
date: 2019-07-23 13:32:59
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Marcus Valtonen &#xd6;rnhag, Carl Olsson, Anders Heyden
mathjax: true
---

* content
{:toc}

##### Abstract
Low rank approximation is a commonly occurring problem in many computer vision and machine learning applications. There are two common ways of optimizing the resulting models. Either the set of matrices with a given rank can be explicitly parametrized using a bilinear factorization, or low rank can be implicitly enforced using regularization terms penalizing non-zero singular values. While the former approach results in differentiable problems that can be efficiently optimized using local quadratic approximation, the latter is typically not differentiable (sometimes even discontinuous) and requires first order subgradient or splitting methods. It is well known that gradient based methods exhibit slow convergence for ill-conditioned problems. 
 In this paper we show how many non-differentiable regularization methods can be reformulated into smooth objectives using bilinear parameterization. This allows us to use standard second order methods, such as Levenberg--Marquardt (LM) and Variable Projection (VarPro), to achieve accurate solutions for ill-conditioned cases. We show on several real and synthetic experiments that our second order formulation converges to substantially more accurate solutions than competing state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11088](http://arxiv.org/abs/1811.11088)

##### PDF
[http://arxiv.org/pdf/1811.11088](http://arxiv.org/pdf/1811.11088)

