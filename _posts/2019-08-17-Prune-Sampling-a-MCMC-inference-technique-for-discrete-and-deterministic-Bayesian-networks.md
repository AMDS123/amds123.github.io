---
layout: post
title: "Prune Sampling: a MCMC inference technique for discrete and deterministic Bayesian networks"
date: 2019-08-17 20:05:23
categories: arXiv_AI
tags: arXiv_AI Inference
author: Frank Phillipson, Jurriaan Parie, Ron Weikamp
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce and characterise the performance of the Markov chain Monte Carlo (MCMC) inference method Prune Sampling for discrete and deterministic Bayesian networks (BNs). We developed a procedure to obtain the performance of a MCMC sampling method in the limit of infinite simulation time, extrapolated from relatively short simulations. This approach was used to conduct a study to compare the accuracy, rate of convergence and the time consumption of Prune Sampling with two conventional MCMC sampling methods: Gibbs- and Metropolis sampling. We show that Markov chains created by Prune Sampling always converge to the desired posterior distribution, also for networks where conventional Gibbs sampling fails. Beside this, we demonstrate that pruning outperforms Gibbs sampling, at least for a certain class of BNs. Though, this tempting feature comes at a price. In the first version of Prune Sampling, for large BNs the procedure to choose the next iteration step uniformly is rather time intensive. Our conclusion is that Prune Sampling is a competitive method for all types of small and medium sized BNs, but (for now) standard methods still perform better for all types of large BNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06335](http://arxiv.org/abs/1908.06335)

##### PDF
[http://arxiv.org/pdf/1908.06335](http://arxiv.org/pdf/1908.06335)

