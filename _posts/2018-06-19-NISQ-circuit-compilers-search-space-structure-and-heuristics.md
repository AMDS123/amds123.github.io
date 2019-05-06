---
layout: post
title: "NISQ circuit compilers: search space structure and heuristics"
date: 2018-06-19 13:58:25
categories: arXiv_CV
tags: arXiv_CV
author: Alexandru Paler, Alwin Zulehner, Robert Wille
mathjax: true
---

* content
{:toc}

##### Abstract
Noisy, intermediate-scale quantum (NISQ) computers are expected to execute quantum circuits of up to a few hundred qubits. The circuits have to satisfy certain constraints concerning the placement and interactions of the involved qubits. Hence, a compiler takes an input circuit not conforming to a NISQ architecture and transforms it to a conforming output circuit. NISQ hardware is faulty and insufficient to implement computational fault-tolerance, such that computation results will be faulty, too. Accordingly, compilers need to optimise the depth and the gate count of the compiled circuits, because these influence the aggregated computation result error. This work discusses the complexity of compilation with a particular focus on the search space structure. The presented analysis decomposes the compilation problem into three combinatorial subproblems for which heuristics can be determined. The search space structure is the result of analysing jointly the gate sequence of the input circuit and its influence on how qubits have to be mapped to a NISQ architecture. These findings support the development of future NISQ compilers.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.07241](https://arxiv.org/abs/1806.07241)

##### PDF
[https://arxiv.org/pdf/1806.07241](https://arxiv.org/pdf/1806.07241)

