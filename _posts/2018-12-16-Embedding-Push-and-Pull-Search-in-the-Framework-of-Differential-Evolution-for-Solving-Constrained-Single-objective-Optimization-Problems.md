---
layout: post
title: "Embedding Push and Pull Search in the Framework of Differential Evolution for Solving Constrained Single-objective Optimization Problems"
date: 2018-12-16 02:52:31
categories: arXiv_AI
tags: arXiv_AI Embedding Optimization
author: Zhun Fan, Wenji Li, Zhaojun Wang, Yutong Yuan, Fuzan Sun, Zhi Yang, Jie Ruan, Zhaocheng Li, Erik Goodman
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a push and pull search method in the framework of differential evolution (PPS-DE) to solve constrained single-objective optimization problems (CSOPs). More specifically, two sub-populations, including the top and bottom sub-populations, are collaborated with each other to search global optimal solutions efficiently. The top sub-population adopts the pull and pull search (PPS) mechanism to deal with constraints, while the bottom sub-population use the superiority of feasible solutions (SF) technique to deal with constraints. In the top sub-population, the search process is divided into two different stages --- push and pull stages.An adaptive DE variant with three trial vector generation strategies is employed in the proposed PPS-DE. In the top sub-population, all the three trial vector generation strategies are used to generate offsprings, just like in CoDE. In the bottom sub-population, a strategy adaptation, in which the trial vector generation strategies are periodically self-adapted by learning from their experiences in generating promising solutions in the top sub-population, is used to choose a suitable trial vector generation strategy to generate one offspring. Furthermore, a parameter adaptation strategy from LSHADE44 is employed in both sup-populations to generate scale factor $F$ and crossover rate $CR$ for each trial vector generation strategy. Twenty-eight CSOPs with 10-, 30-, and 50-dimensional decision variables provided in the CEC2018 competition on real parameter single objective optimization are optimized by the proposed PPS-DE. The experimental results demonstrate that the proposed PPS-DE has the best performance compared with the other seven state-of-the-art algorithms, including AGA-PPS, LSHADE44, LSHADE44+IDE, UDE, IUDE, $\epsilon$MAg-ES and C$^2$oDE.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06381](http://arxiv.org/abs/1812.06381)

##### PDF
[http://arxiv.org/pdf/1812.06381](http://arxiv.org/pdf/1812.06381)

