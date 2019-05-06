---
layout: post
title: "A Speculative Parallel DFA Membership Test for Multicore, SIMD and Cloud Computing Environments"
date: 2013-07-22 15:32:29
categories: arXiv_CV
tags: arXiv_CV
author: Yousun Ko, Minyoung Jung, Yo-Sub Han, Bernd Burgstaller
mathjax: true
---

* content
{:toc}

##### Abstract
We present techniques to parallelize membership tests for Deterministic Finite Automata (DFAs). Our method searches arbitrary regular expressions by matching multiple bytes in parallel using speculation. We partition the input string into chunks, match chunks in parallel, and combine the matching results. Our parallel matching algorithm exploits structural DFA properties to minimize the speculative overhead. Unlike previous approaches, our speculation is failure-free, i.e., (1) sequential semantics are maintained, and (2) speed-downs are avoided altogether. On architectures with a SIMD gather-operation for indexed memory loads, our matching operation is fully vectorized. The proposed load-balancing scheme uses an off-line profiling step to determine the matching capacity of each par- ticipating processor. Based on matching capacities, DFA matches are load-balanced on inhomogeneous parallel architectures such as cloud computing environments. We evaluated our speculative DFA membership test for a representative set of benchmarks from the Perl-compatible Regular Expression (PCRE) library and the PROSITE protein database. Evaluation was conducted on a 4 CPU (40 cores) shared-memory node of the Intel Manycore Testing Lab (Intel MTL), on the Intel AVX2 SDE simulator for 8-way fully vectorized SIMD execution, and on a 20-node (288 cores) cluster on the Amazon EC2 computing cloud.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1210.5093](https://arxiv.org/abs/1210.5093)

##### PDF
[https://arxiv.org/pdf/1210.5093](https://arxiv.org/pdf/1210.5093)

