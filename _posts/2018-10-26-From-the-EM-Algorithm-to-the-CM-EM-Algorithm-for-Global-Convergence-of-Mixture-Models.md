---
layout: post
title: "From the EM Algorithm to the CM-EM Algorithm for Global Convergence of Mixture Models"
date: 2018-10-26 08:44:50
categories: arXiv_AI
tags: arXiv_AI
author: Chenguang Lu
mathjax: true
---

* content
{:toc}

##### Abstract
The Expectation-Maximization (EM) algorithm for mixture models often results in slow or invalid convergence. The popular convergence proof affirms that the likelihood increases with Q; Q is increasing in the M -step and non-decreasing in the E-step. The author found that (1) Q may and should decrease in some E-steps; (2) The Shannon channel from the E-step is improper and hence the expectation is improper. The author proposed the CM-EM algorithm (CM means Channel's Matching), which adds a step to optimize the mixture ratios for the proper Shannon channel and maximizes G, average log-normalized-likelihood, in the M-step. Neal and Hinton's Maximization-Maximization (MM) algorithm use F instead of Q to speed the convergence. Maximizing G is similar to maximizing F. The new convergence proof is similar to Beal's proof with the variational method. It first proves that the minimum relative entropy equals the minimum R-G (R is mutual information), then uses variational and iterative methods that Shannon et al. use for rate-distortion functions to prove the global convergence. Some examples show that Q and F should and may decrease in some E-steps. For the same example, the EM, MM, and CM-EM algorithms need about 36, 18, and 9 iterations respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11227](http://arxiv.org/abs/1810.11227)

##### PDF
[http://arxiv.org/pdf/1810.11227](http://arxiv.org/pdf/1810.11227)

