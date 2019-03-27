---
layout: post
title: "Extracting Success from IBM's 20-Qubit Machines Using Error-Aware Compilation"
date: 2019-03-26 15:43:36
categories: arXiv_CL
tags: arXiv_CL
author: Shin Nishio, Yulu Pan, Takahiko Satoh, Hideharu Amano, Rodney Van Meter
mathjax: true
---

* content
{:toc}

##### Abstract
NISQ (Noisy, Intermediate-Scale Quantum) computing requires error mitigation to achieve meaningful computation. Our compilation tool development focuses on the fact that the error rates of individual qubits are not equal, with a goal of maximizing the success probability of real-world subroutines such as an adder circuit. We begin by establishing a metric for choosing among possible paths and circuit alternatives for executing gates between variables placed far apart within the processor, and test our approach on two IBM 20-qubit systems named Tokyo and Poughkeepsie. We find that a single-number metric describing the fidelity of individual gates is a useful but imperfect guide. Our compiler uses this subsystem and maps complete circuits onto the machine using a beam search-based heuristic that will scale as processor and program sizes grow. To evaluate the whole compilation process, we compiled and executed adder circuits, then calculated the KL-divergence (a measure of the distance between two probability distributions). For a circuit within the capabilities of the hardware, our compilation increases estimated success probability and reduces KL-divergence relative to an error-oblivious placement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10963](http://arxiv.org/abs/1903.10963)

##### PDF
[http://arxiv.org/pdf/1903.10963](http://arxiv.org/pdf/1903.10963)

