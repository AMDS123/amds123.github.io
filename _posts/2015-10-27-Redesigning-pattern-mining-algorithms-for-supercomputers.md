---
layout: post
title: "Redesigning pattern mining algorithms for supercomputers"
date: 2015-10-27 06:59:14
categories: arXiv_CV
tags: arXiv_CV GAN
author: Kazuki Yoshizoe, Aika Terada, Koji Tsuda
mathjax: true
---

* content
{:toc}

##### Abstract
Upcoming many core processors are expected to employ a distributed memory architecture similar to currently available supercomputers, but parallel pattern mining algorithms amenable to the architecture are not comprehensively studied. We present a novel closed pattern mining algorithm with a well-engineered communication protocol, and generalize it to find statistically significant patterns from personal genome data. For distributing communication evenly, it employs global load balancing with multiple stacks distributed on a set of cores organized as a hypercube with random edges. Our algorithm achieved up to 1175-fold speedup by using 1200 cores for solving a problem with 11,914 items and 697 transactions, while the naive approach of separating the search space failed completely.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1510.07787](https://arxiv.org/abs/1510.07787)

##### PDF
[https://arxiv.org/pdf/1510.07787](https://arxiv.org/pdf/1510.07787)

