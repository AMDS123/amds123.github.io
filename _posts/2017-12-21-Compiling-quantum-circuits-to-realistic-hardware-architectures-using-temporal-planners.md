---
layout: post
title: "Compiling quantum circuits to realistic hardware architectures using temporal planners"
date: 2017-12-21 10:41:42
categories: arXiv_AI
tags: arXiv_AI QA
author: Davide Venturelli, Minh Do, Eleanor Rieffel, Jeremy Frank
mathjax: true
---

* content
{:toc}

##### Abstract
To run quantum algorithms on emerging gate-model quantum hardware, quantum circuits must be compiled to take into account constraints on the hardware. For near-term hardware, with only limited means to mitigate decoherence, it is critical to minimize the duration of the circuit. We investigate the application of temporal planners to the problem of compiling quantum circuits to newly emerging quantum hardware. While our approach is general, we focus on compiling to superconducting hardware architectures with nearest neighbor constraints. Our initial experiments focus on compiling Quantum Alternating Operator Ansatz (QAOA) circuits whose high number of commuting gates allow great flexibility in the order in which the gates can be applied. That freedom makes it more challenging to find optimal compilations but also means there is a greater potential win from more optimized compilation than for less flexible circuits. We map this quantum circuit compilation problem to a temporal planning problem, and generated a test suite of compilation problems for QAOA circuits of various sizes to a realistic hardware architecture. We report compilation results from several state-of-the-art temporal planners on this test set. This early empirical evaluation demonstrates that temporal planning is a viable approach to quantum circuit compilation.

##### Abstract (translated by Google)
为了在新兴的门模型量子硬件上运行量子算法，量子电路必须被编译来考虑硬件的限制。对于近期的硬件来说，只有有限的手段来减少退相干，关键是要缩短电路的持续时间。我们调查时间计划者的应用程序编译量子电路到新出现的量子硬件的问题。虽然我们的方法是一般的，但我们专注于编译超导硬件架构与最近的邻居约束。我们最初的实验着重于编译量子交换算子Ansatz（QAOA）电路，其中大量的通勤门允许门的可应用顺序有很大的灵活性。这种自由使得寻找最佳编辑更具挑战性，但也意味着更好的编译比不灵活的电路有更大的潜力。我们将这个量子电路编译问题映射到一个时间规划问题上，并且为各种尺寸的QAOA电路产生了一个编译问题的测试套件，以实际的硬件结构。我们在这个测试集上汇报了来自几个最先进的时间计划者的汇编结果。这个早期的经验评估表明时间规划是量子电路编译的一个可行的方法。

##### URL
[http://arxiv.org/abs/1705.08927](http://arxiv.org/abs/1705.08927)

##### PDF
[http://arxiv.org/pdf/1705.08927](http://arxiv.org/pdf/1705.08927)

