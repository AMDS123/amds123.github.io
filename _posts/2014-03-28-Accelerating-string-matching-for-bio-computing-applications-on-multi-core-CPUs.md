---
layout: post
title: "Accelerating string matching for bio-computing applications on multi-core CPUs"
date: 2014-03-28 07:44:23
categories: arXiv_CV
tags: arXiv_CV
author: D. Herath, C. Lakmali, R. G. Ragel
mathjax: true
---

* content
{:toc}

##### Abstract
Huge amount of data in the form of strings are being handled in bio-computing applications and searching algorithms are quite frequently used in them. Many methods utilizing on both software and hardware are being proposed to accelerate processing of such data. The typical hardware-based acceleration techniques either require special hardware such as general purpose graphics processing units (GPGPUs) or need building a new hardware such as an FPGA based design. On the other hard, software-based acceleration techniques are easier since they only require some changes in the software code or the software architecture. Typical software-based techniques make use of computers connected over a network, also known as a network grid to accelerate the processing. In this paper, we test the hypothesis that multi-core architectures should provide better performance in this kind of computation, but still it would depend on the algorithm selected as well as the programming model being utilized. We present the acceleration of a string-searching algorithm on a multi-core CPU via a POSIX thread based implementation. Our implementation on an 8-core processor (that supports 16-threads) resulted in 9x throughput improvement compared to a single thread implementation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1403.7294](https://arxiv.org/abs/1403.7294)

##### PDF
[https://arxiv.org/pdf/1403.7294](https://arxiv.org/pdf/1403.7294)

