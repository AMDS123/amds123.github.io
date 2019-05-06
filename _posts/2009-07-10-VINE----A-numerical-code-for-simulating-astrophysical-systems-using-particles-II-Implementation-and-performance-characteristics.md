---
layout: post
title: "VINE -- A numerical code for simulating astrophysical systems using particles II: Implementation and performance characteristics"
date: 2009-07-10 21:04:42
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Andrew F. Nelson (1), M. Wetzstein (2,3), T. Naab (3,4). (1=LANL HPC-5, 2=Dept of Astrophysical Sciences Princeton, 3=Universitaets Sternwarte Muenchen, 4=Inst of Astronomy, Cambridge)
mathjax: true
---

* content
{:toc}

##### Abstract
We continue our presentation of VINE. We begin with a description of relevant architectural properties of the serial and shared memory parallel computers on which VINE is intended to run, and describe their influences on the design of the code itself. We continue with a detailed description of a number of optimizations made to the layout of the particle data in memory and to our implementation of a binary tree used to access that data for use in gravitational force calculations and searches for SPH neighbor particles. We describe modifications to the code necessary to obtain forces efficiently from special purpose `GRAPE' hardware. We conclude with an extensive series of performance tests, which demonstrate that the code can be run efficiently and without modification in serial on small workstations or in parallel using OpenMP compiler directives on large scale, shared memory parallel machines. We analyze the effects of the code optimizations and estimate that they improve its overall performance by more than an order of magnitude over that obtained by many other tree codes. Scaled parallel performance of the gravity and SPH calculations, together the most costly components of most simulations, is nearly linear up to maximum machine sizes available to us (120 processors on an Origin~3000). At similar accuracy, performance of VINE, used in GRAPE-tree mode, is approximately a factor two slower than that of VINE, used in host-only mode. Optimizations of the GRAPE/host communications could improve the speed by as much as a factor of three, but have not yet been implemented in VINE.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0802.4253](https://arxiv.org/abs/0802.4253)

##### PDF
[https://arxiv.org/pdf/0802.4253](https://arxiv.org/pdf/0802.4253)

