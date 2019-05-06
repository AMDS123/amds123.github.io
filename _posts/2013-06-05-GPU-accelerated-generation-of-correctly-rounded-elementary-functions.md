---
layout: post
title: "GPU-accelerated generation of correctly-rounded elementary functions"
date: 2013-06-05 11:51:55
categories: arXiv_CV
tags: arXiv_CV
author: Pierre Fortin (LIP6), Mourad Gouicem (LIP6), Stef Graillat (LIP6)
mathjax: true
---

* content
{:toc}

##### Abstract
The IEEE 754-2008 standard recommends the correct rounding of some elementary functions. This requires to solve the Table Maker's Dilemma which implies a huge amount of CPU computation time. We consider in this paper accelerating such computations, namely Lefe'vre algorithm on Graphics Processing Units (GPUs) which are massively parallel architectures with a partial SIMD execution (Single Instruction Multiple Data). We first propose an analysis of the Lefèvre hard-to-round argument search using the concept of continued fractions. We then propose a new parallel search algorithm much more efficient on GPU thanks to its more regular control flow. We also present an efficient hybrid CPU-GPU deployment of the generation of the polynomial approximations required in Lefèvre algorithm. In the end, we manage to obtain overall speedups up to 53.4x on one GPU over a sequential CPU execution, and up to 7.1x over a multi-core CPU, which enable a much faster solving of the Table Maker's Dilemma for the double precision format.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1211.3056](https://arxiv.org/abs/1211.3056)

##### PDF
[https://arxiv.org/pdf/1211.3056](https://arxiv.org/pdf/1211.3056)

