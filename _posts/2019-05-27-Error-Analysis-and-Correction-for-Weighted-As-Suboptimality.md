---
layout: post
title: "Error Analysis and Correction for Weighted A*'s Suboptimality"
date: 2019-05-27 17:08:08
categories: arXiv_AI
tags: arXiv_AI
author: Robert C. Holte, Ruben Majadas, Alberto Pozanco, Daniel Borrajo
mathjax: true
---

* content
{:toc}

##### Abstract
Weighted A* (wA*) is a widely used algorithm for rapidly, but suboptimally, solving planning and search problems. The cost of the solution it produces is guaranteed to be at most W times the optimal solution cost, where W is the weight wA* uses in prioritizing open nodes. W is therefore a suboptimality bound for the solution produced by wA*. There is broad consensus that this bound is not very accurate, that the actual suboptimality of wA*'s solution is often much less than W times optimal. However, there is very little published evidence supporting that view, and no existing explanation of why W is a poor bound. This paper fills in these gaps in the literature. We begin with a large-scale experiment demonstrating that, across a wide variety of domains and heuristics for those domains, W is indeed very often far from the true suboptimality of wA*'s solution. We then analytically identify the potential sources of error. Finally, we present a practical method for correcting for two of these sources of error and experimentally show that the correction frequently eliminates much of the error.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11346](https://arxiv.org/abs/1905.11346)

##### PDF
[https://arxiv.org/pdf/1905.11346](https://arxiv.org/pdf/1905.11346)

