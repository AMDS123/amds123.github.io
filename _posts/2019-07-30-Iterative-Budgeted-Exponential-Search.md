---
layout: post
title: "Iterative Budgeted Exponential Search"
date: 2019-07-30 16:40:41
categories: arXiv_AI
tags: arXiv_AI
author: Malte Helmert, Tor Lattimore, Levi H. S. Lelis, Laurent Orseau, Nathan R. Sturtevant
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle two long-standing problems related to re-expansions in heuristic search algorithms. For graph search, A* can require $\Omega(2^{n})$ expansions, where $n$ is the number of states within the final $f$ bound. Existing algorithms that address this problem like B and B' improve this bound to $\Omega(n^2)$. For tree search, IDA* can also require $\Omega(n^2)$ expansions. We describe a new algorithmic framework that iteratively controls an expansion budget and solution cost limit, giving rise to new graph and tree search algorithms for which the number of expansions is $O(n \log C)$, where $C$ is the optimal solution cost. Our experiments show that the new algorithms are robust in scenarios where existing algorithms fail. In the case of tree search, our new algorithms have no overhead over IDA* in scenarios to which IDA* is well suited and can therefore be recommended as a general replacement for IDA*.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13062](http://arxiv.org/abs/1907.13062)

##### PDF
[http://arxiv.org/pdf/1907.13062](http://arxiv.org/pdf/1907.13062)

