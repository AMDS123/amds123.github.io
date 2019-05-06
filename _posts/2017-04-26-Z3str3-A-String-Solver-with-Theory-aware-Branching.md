---
layout: post
title: "Z3str3: A String Solver with Theory-aware Branching"
date: 2017-04-26 00:02:12
categories: arXiv_CV
tags: arXiv_CV
author: Murphy Berzish, Yunhui Zheng, Vijay Ganesh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new string SMT solver, Z3str3, that is faster than its competitors Z3str2, Norn, CVC4, S3, and S3P over a majority of three industrial-strength benchmarks, namely Kaluza, PISA, and IBM AppScan. Z3str3 supports string equations, linear arithmetic over length function, and regular language membership predicate. The key algorithmic innovation behind the efficiency of Z3str3 is a technique we call theory-aware branching, wherein we modify Z3's branching heuristic to take into account the structure of theory literals to compute branching activities. In the traditional DPLL(T) architecture, the structure of theory literals is hidden from the DPLL(T) SAT solver because of the Boolean abstraction constructed over the input theory formula. By contrast, the theory-aware technique presented in this paper exposes the structure of theory literals to the DPLL(T) SAT solver's branching heuristic, thus enabling it to make much smarter decisions during its search than otherwise. As a consequence, Z3str3 has better performance than its competitors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.07935](https://arxiv.org/abs/1704.07935)

##### PDF
[https://arxiv.org/pdf/1704.07935](https://arxiv.org/pdf/1704.07935)

