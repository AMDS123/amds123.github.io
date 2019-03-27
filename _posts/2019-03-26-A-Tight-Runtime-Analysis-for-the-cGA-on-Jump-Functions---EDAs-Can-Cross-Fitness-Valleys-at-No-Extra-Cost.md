---
layout: post
title: "A Tight Runtime Analysis for the cGA on Jump Functions---EDAs Can Cross Fitness Valleys at No Extra Cost"
date: 2019-03-26 16:12:02
categories: arXiv_AI
tags: arXiv_AI
author: Benjamin Doerr
mathjax: true
---

* content
{:toc}

##### Abstract
We prove that the compact genetic algorithm (cGA) with hypothetical population size $\mu = \Omega(\sqrt n \log n) \cap \text{poly}(n)$ with high probability finds the optimum of any $n$-dimensional jump function with jump size $k < \frac 1 {20} \ln n$ in $O(\mu \sqrt n)$ iterations. Since it is known that the cGA with high probability needs at least $\Omega(\mu \sqrt n + n \log n)$ iterations to optimize the unimodal OneMax function, our result shows that the cGA in contrast to most classic evolutionary algorithms here is able to cross moderate-sized valleys of low fitness at no extra cost. Our runtime guarantee improves over the recent upper bound $O(\mu n^{1.5} \log n)$ valid for $\mu = \Omega(n^{3.5+\varepsilon})$ of Hasenöhrl and Sutton (GECCO 2018). For the best choice of the hypothetical population size, this result gives a runtime guarantee of $O(n^{5+\varepsilon})$, whereas ours gives $O(n \log n)$. We also provide a simple general method based on parallel runs that, under mild conditions, (i)~overcomes the need to specify a suitable population size, but gives a performance close to the one stemming from the best-possible population size, and (ii)~transforms EDAs with high-probability performance guarantees into EDAs with similar bounds on the expected runtime.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.10983](https://arxiv.org/abs/1903.10983)

##### PDF
[https://arxiv.org/pdf/1903.10983](https://arxiv.org/pdf/1903.10983)

