---
layout: post
title: "Regret Minimisation in Multi-Armed Bandits Using Bounded Arm Memory"
date: 2019-01-24 12:56:46
categories: arXiv_AI
tags: arXiv_AI
author: Arghya Roy Chaudhuri, Shivaram Kalyanakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a constant word (RAM model) algorithm for regret minimisation for both finite and infinite Stochastic Multi-Armed Bandit (MAB) instances. Most of the existing regret minimisation algorithms need to remember the statistics of all the arms they encounter. This may become a problem for the cases where the number of available words of memory is limited. Designing an efficient regret minimisation algorithm that uses a constant number of words has long been interesting to the community. Some early attempts consider the number of arms to be infinite, and require the reward distribution of the arms to belong to some particular family. Recently, for finitely many-armed bandits an explore-then-commit based algorithm~\citep{Liau+PSY:2018} seems to escape such assumption. However, due to the underlying PAC-based elimination their method incurs a high regret. We present a conceptually simple, and efficient algorithm that needs to remember statistics of at most $M$ arms, and for any $K$-armed finite bandit instance it enjoys a $O(KM +K^{1.5}\sqrt{T\log (T/MK)}/M)$ upper-bound on regret. We extend it to achieve sub-linear \textit{quantile-regret}~\citep{RoyChaudhuri+K:2018} and empirically verify the efficiency of our algorithm via experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08387](http://arxiv.org/abs/1901.08387)

##### PDF
[http://arxiv.org/pdf/1901.08387](http://arxiv.org/pdf/1901.08387)

