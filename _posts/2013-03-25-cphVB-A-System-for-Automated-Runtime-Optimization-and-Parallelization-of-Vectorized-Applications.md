---
layout: post
title: "cphVB: A System for Automated Runtime Optimization and Parallelization of Vectorized Applications"
date: 2013-03-25 15:18:56
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Mads Ruben Burgdorff Kristensen, Simon Andreas Frimann Lund, Troels Blum, Brian Vinter
mathjax: true
---

* content
{:toc}

##### Abstract
Modern processor architectures, in addition to having still more cores, also require still more consideration to memory-layout in order to run at full capacity. The usefulness of most languages is deprecating as their abstractions, structures or objects are hard to map onto modern processor architectures efficiently. The work in this paper introduces a new abstract machine framework, cphVB, that enables vector oriented high-level programming languages to map onto a broad range of architectures efficiently. The idea is to close the gap between high-level languages and hardware optimized low-level implementations. By translating high-level vector operations into an intermediate vector bytecode, cphVB enables specialized vector engines to efficiently execute the vector operations. The primary success parameters are to maintain a complete abstraction from low-level details and to provide efficient code execution across different, modern, processors. We evaluate the presented design through a setup that targets multi-core CPU architectures. We evaluate the performance of the implementation using Python implementations of well-known algorithms: a jacobi solver, a kNN search, a shallow water simulation and a synthetic stencil simulation. All demonstrate good performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1210.7774](https://arxiv.org/abs/1210.7774)

##### PDF
[https://arxiv.org/pdf/1210.7774](https://arxiv.org/pdf/1210.7774)

