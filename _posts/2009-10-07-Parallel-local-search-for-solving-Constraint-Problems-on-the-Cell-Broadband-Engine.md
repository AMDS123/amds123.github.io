---
layout: post
title: "Parallel local search for solving Constraint Problems on the Cell Broadband Engine"
date: 2009-10-07 13:44:11
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Salvator Abreu, Daniel Diaz, Philippe Codognet
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the use of the Cell Broadband Engine (Cell/BE for short) for combinatorial optimization applications: we present a parallel version of a constraint-based local search algorithm that has been implemented on a multiprocessor BladeCenter machine with twin Cell/BE processors (total of 16 SPUs per blade). This algorithm was chosen because it fits very well the Cell/BE architecture and requires neither shared memory nor communication between processors, while retaining a compact memory footprint. We study the performance on several large optimization benchmarks and show that this achieves mostly linear time speedups, even sometimes super-linear. This is possible because the parallel implementation might explore simultaneously different parts of the search space and therefore converge faster towards the best sub-space and thus towards a solution. Besides getting speedups, the resulting times exhibit a much smaller variance, which benefits applications where a timely reply is critical.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0910.1264](https://arxiv.org/abs/0910.1264)

##### PDF
[https://arxiv.org/pdf/0910.1264](https://arxiv.org/pdf/0910.1264)

