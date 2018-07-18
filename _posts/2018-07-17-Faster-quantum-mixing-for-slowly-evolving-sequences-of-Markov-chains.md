---
layout: post
title: "Faster quantum mixing for slowly evolving sequences of Markov chains"
date: 2018-07-17 15:20:37
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Davide Orsucci, Hans J. Briegel, Vedran Dunjko
mathjax: true
---

* content
{:toc}

##### Abstract
Markov chain methods are remarkably successful in computational physics, machine learning, and combinatorial optimization. The cost of such methods often reduces to the mixing time, i.e. \ the time required to reach the steady state of the Markov chain, which scales as $\delta^{-1}$, the inverse of the spectral gap. It has long been conjectured that quantum computers offer nearly generic quadratic improvements for mixing problems. However, except in special cases, quantum algorithms achieve a run-time of $\O(\sqrt{\delta^{-1}} \sqrt{N})$, which introduces a costly dependence on the Markov chain size $N,$ not present in the classical case. Here, we re-address the problem of mixing of Markov chains when these form a slowly evolving sequence. This setting is akin to the simulated annealing setting, and is commonly encountered in physics, material sciences and machine learning. We provide a quantum memory-efficient algorithm with a run-time of $\O(\sqrt{\delta^{-1}} \sqrt[4]{N})$, neglecting logarithmic terms, which is an important improvement for large state spaces. Further our algorithms output quantum encodings of distributions, which has advantages over classical outputs. Finally, we discuss the run-time bounds of mixing algorithms and show that, under certain assumptions, our algorithms are optimal.

##### Abstract (translated by Google)
马尔可夫链方法在计算物理，机器学习和组合优化方面非常成功。这种方法的成本通常会降低到混合时间，即达到马尔可夫链稳定状态所需的时间，其延伸为$ \ delta ^ { -  1} $，即光谱间隙的倒数。长期以来人们猜测，量子计算机为混合问题提供了几乎普遍的二次改进。但是，除特殊情况外，量子算法实现了$ \ O（\ sqrt {\ delta ^ { -  1}} \ sqrt {N}）$的运行时间，这引入了对马尔可夫链大小$ N的昂贵依赖性。 ，$经典案例中没有。在这里，我们重新解决马尔可夫链混合的问题，当这些链形成一个缓慢进化的序列。此设置类似于模拟退火设置，在物理，材料科学和机器学习中经常遇到。我们提供了一个量子存储效率算法，其运行时间为$ \ O（\ sqrt {\ delta ^ { -  1}} \ sqrt [4] {N}）$，忽略了对数项，这是一个重要的改进，大型国家空间。此外，我们的算法输出分布的量子编码，这比传统输出具有优势。最后，我们讨论混合算法的运行时间界限，并表明在某些假设下，我们的算法是最优的。

##### URL
[http://arxiv.org/abs/1503.01334](http://arxiv.org/abs/1503.01334)

##### PDF
[http://arxiv.org/pdf/1503.01334](http://arxiv.org/pdf/1503.01334)

