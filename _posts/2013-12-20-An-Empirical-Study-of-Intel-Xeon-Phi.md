---
layout: post
title: "An Empirical Study of Intel Xeon Phi"
date: 2013-12-20 09:05:07
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jianbin Fang, Ana Lucia Varbanescu, Henk Sips, Lilun Zhang, Yonggang Che, Chuanfu Xu
mathjax: true
---

* content
{:toc}

##### Abstract
With at least 50 cores, Intel Xeon Phi is a true many-core architecture. Featuring fairly powerful cores, two cache levels, and very fast interconnections, the Xeon Phi can get a theoretical peak of 1000 GFLOPs and over 240 GB/s. These numbers, as well as its flexibility - it can be used both as a coprocessor or as a stand-alone processor - are very tempting for parallel applications looking for new performance records. In this paper, we present an empirical study of Xeon Phi, stressing its performance limits and relevant performance factors, ultimately aiming to present a simplified view of the machine for regular programmers in search for performance. To do so, we have micro-benchmarked the main hardware components of the processor - the cores, the memory hierarchies, the ring interconnect, and the PCIe connection. We show that, in ideal microbenchmarking conditions, the performance that can be achieved is very close to the theoretical peak, as given in the official programmer's guide. We have also identified and quantified several causes for significant performance penalties. Our findings have been captured in four optimization guidelines, and used to build a simplified programmer's view of Xeon Phi, eventually enable the design and prototyping of applications on a functionality-based model of the architecture.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1310.5842](https://arxiv.org/abs/1310.5842)

##### PDF
[https://arxiv.org/pdf/1310.5842](https://arxiv.org/pdf/1310.5842)

