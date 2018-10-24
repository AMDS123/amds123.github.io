---
layout: post
title: "Deterministic Approximate Methods for Maximum Consensus Robust Fitting"
date: 2018-10-23 04:56:16
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Huu Le, Tat-Jun Chin, Anders Eriksson, Thanh-Toan Do, David Suter
mathjax: true
---

* content
{:toc}

##### Abstract
Maximum consensus estimation plays a critically important role in robust fitting problems in computer vision. Currently, the most prevalent algorithms for consensus maximization draw from the class of randomized hypothesize-and-verify algorithms, which are cheap but can usually deliver only rough approximate solutions. On the other extreme, there are exact algorithms which are exhaustive search in nature and can be costly for practical-sized inputs. This paper fills the gap between the two extremes by proposing deterministic algorithms to approximately optimize the maximum consensus criterion. Our work begins by reformulating consensus maximization with linear complementarity constraints. Then, we develop two novel algorithms: one based on non-smooth penalty method with a Frank-Wolfe style optimization scheme, the other based on the Alternating Direction Method of Multipliers (ADMM). Both algorithms solve convex subproblems to efficiently perform the optimization. We demonstrate the capability of our algorithms to greatly improve a rough initial estimate, such as those obtained using least squares or a randomized algorithm. Compared to the exact algorithms, our approach is much more practical on realistic input sizes. Further, our approach is naturally applicable to estimation problems with geometric residuals

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.10003](http://arxiv.org/abs/1710.10003)

##### PDF
[http://arxiv.org/pdf/1710.10003](http://arxiv.org/pdf/1710.10003)

