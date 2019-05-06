---
layout: post
title: "Autotuning GPU Kernels via Static and Predictive Analysis"
date: 2017-06-29 11:25:02
categories: arXiv_CV
tags: arXiv_CV
author: Robert V. Lim, Boyana Norris, Allen D. Malony
mathjax: true
---

* content
{:toc}

##### Abstract
Optimizing the performance of GPU kernels is challenging for both human programmers and code generators. For example, CUDA programmers must set thread and block parameters for a kernel, but might not have the intuition to make a good choice. Similarly, compilers can generate working code, but may miss tuning opportunities by not targeting GPU models or performing code transformations. Although empirical autotuning addresses some of these challenges, it requires extensive experimentation and search for optimal code variants. This research presents an approach for tuning CUDA kernels based on static analysis that considers fine-grained code structure and the specific GPU architecture features. Notably, our approach does not require any program runs in order to discover near-optimal parameter settings. We demonstrate the applicability of our approach in enabling code autotuners such as Orio to produce competitive code variants comparable with empirical-based methods, without the high cost of experiments.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1701.08547](https://arxiv.org/abs/1701.08547)

##### PDF
[https://arxiv.org/pdf/1701.08547](https://arxiv.org/pdf/1701.08547)

