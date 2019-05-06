---
layout: post
title: "Brute-forcing spin-glass problems with CUDA"
date: 2019-04-07 10:34:42
categories: arXiv_CV
tags: arXiv_CV
author: Konrad Jałowiecki, Marek M. Rams, Bartłomiej Gardas
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate how to compute the low energy spectrum for small ($L\le 50$), but otherwise arbitrary, spin-glass instances using modern Graphics Processing Units or a similar heterogeneous architecture. Our algorithm performs an exhaustive (i.e. brute-force) search of all possible configurations to select $N\ll 2^L$ lowest ones together with their corresponding energies. We mainly focus on the Ising model defined on an arbitrary graph. An open source implementation based on CUDA Fortran and a suitable python wrapper are provided. As opposed to heuristic approaches ours is exact and thus can serve as a references point to benchmark other algorithms and hardware, including quantum and digital annealers. Our implementation offers unprecedented speed and efficiency already visible on commodity hardware. At the same time, it can be easily launched on professional, high-end, graphics cards virtually at no extra effort. As a practical application, we employ it to demonstrate that despite its one-dimensional nature, the recent Matrix Product State based algorithm can still accurately approximate the low energy spectrum of fully connected graphs of size $L$ approaching $50$.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.03621](https://arxiv.org/abs/1904.03621)

##### PDF
[https://arxiv.org/pdf/1904.03621](https://arxiv.org/pdf/1904.03621)

