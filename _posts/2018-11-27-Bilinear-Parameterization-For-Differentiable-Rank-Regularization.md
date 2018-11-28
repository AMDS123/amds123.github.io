---
layout: post
title: "Bilinear Parameterization For Differentiable Rank-Regularization"
date: 2018-11-27 16:48:11
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Marcus Valtonen &#xd6;rnhag, Carl Olsson, Anders Heyden
mathjax: true
---

* content
{:toc}

##### Abstract
Low rank approximation is a commonly occurring problem in many computer vision and machine learning applications. There are two common ways of optimizing the resulting models. Either the set of matrices with a given sought rank can be explicitly parametrized using a bilinear factorization, or low rank can be implicitly enforced using regularization terms penalizing non-zero singular values. While the former results in differentiable problems that can be efficiently optimized using local quadratic approximation the latter are typically not differentiable (sometimes even discontinuous) and require splitting methods such as Alternating Direction Method of Multipliers (ADMM). It is well known that while ADMM makes rapid improvements the first couple of iterations convergence to the exact minimizer can be tediously slow. On the other hand regularization formulations can in certain cases come with theoretical optimality guarantees. 
 In this paper we show how many non-differentiable regularization methods can be reformulated into smooth objectives using bilinear parameterization. This opens up the possibility of using second order methods such as Levenberg--Marquardt (LM) and Variable Projection (VarPro) to achieve accurate solutions for ill-conditioned problems. We show on several real and synthetic experiments that our second order formulation converges to substantially more accurate solutions than what ADMM formulations provide in a reasonable amount of time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11088](http://arxiv.org/abs/1811.11088)

##### PDF
[http://arxiv.org/pdf/1811.11088](http://arxiv.org/pdf/1811.11088)

