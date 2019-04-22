---
layout: post
title: "Runtime Analysis of the Univariate Marginal Distribution Algorithm under Low Selective Pressure and Prior Noise"
date: 2019-04-19 15:49:27
categories: arXiv_AI
tags: arXiv_AI Relation
author: Per Kristian Lehre, Phan Trung Hai Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
We perform a rigorous runtime analysis for the Univariate Marginal Distribution Algorithm on the LeadingOnes function, a well-known benchmark function in the theory community of evolutionary computation with a high correlation between decision variables. For a problem instance of size $n$, the currently best known upper bound on the expected runtime is $\mathcal{O}(n\lambda\log\lambda+n^2)$ (Dang and Lehre, GECCO 2015), while a lower bound necessary to understand how the algorithm copes with variable dependencies is still missing. Motivated by this, we show that the algorithm requires a $e^{\Omega(\mu)}$ runtime with high probability and in expectation if the selective pressure is low; otherwise, we obtain a lower bound of $\Omega(\frac{n\lambda}{\log(\lambda-\mu)})$ on the expected runtime. Furthermore, we for the first time consider the algorithm on the function under a prior noise model and obtain an $\mathcal{O}(n^2)$ expected runtime for the optimal parameter settings. In the end, our theoretical results are accompanied by empirical findings, not only matching with rigorous analyses but also providing new insights into the behaviour of the algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09239](http://arxiv.org/abs/1904.09239)

##### PDF
[http://arxiv.org/pdf/1904.09239](http://arxiv.org/pdf/1904.09239)

