---
layout: post
title: "Comparison of Lattice-Free and Lattice-Based Sequence Discriminative Training Criteria for LVCSR"
date: 2019-07-01 15:16:04
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Wilfried Michel, Ralf Schl&#xfc;ter, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence discriminative training criteria have long been a standard tool in automatic speech recognition for improving the performance of acoustic models over their maximum likelihood / cross entropy trained counterparts. While previously a lattice approximation of the search space has been necessary to reduce computational complexity, recently proposed methods use other approximations to dispense of the need for the computationally expensive step of separate lattice creation. 
 In this work we present a memory efficient implementation of the forward-backward computation that allows us to use uni-gram word-level language models in the denominator calculation while still doing a full summation on GPU. This allows for a direct comparison of lattice-based and lattice-free sequence discriminative training criteria such as MMI and sMBR, both using the same language model during training. 
 We compared performance, speed of convergence, and stability on large vocabulary continuous speech recognition tasks like Switchboard and Quaero. We found that silence modeling seriously impacts the performance in the lattice-free case and needs special treatment. In our experiments lattice-free MMI comes on par with its lattice-based counterpart. Lattice-based sMBR still outperforms all lattice-free training criteria.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01409](http://arxiv.org/abs/1907.01409)

##### PDF
[http://arxiv.org/pdf/1907.01409](http://arxiv.org/pdf/1907.01409)

