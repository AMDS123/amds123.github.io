---
layout: post
title: "The Apertif Monitor for Bursts Encountered in Real-time auto-tuning optimization with genetic algorithms"
date: 2018-11-10 00:18:40
categories: arXiv_CV
tags: arXiv_CV Survey Optimization Detection
author: Klim Mikhailov, Alessio Sclocco
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time searches for faint radio pulses from unknown radio transients are computationally challenging. Detections become further complicated due to continuously increasing technical capabilities of transient surveys: telescope sensitivity, searched area of the sky, number of antennas or dishes, temporal and frequency resolution. The new Apertif transient survey on the Westerbork telescope happens in real-time on GPUs by means of the single-pulse search pipeline AMBER (Sclocco, 2017). AMBER initially carries out auto tuning: it finds the most optimal configuration of user-controlled parameters per each of four pipeline kernels so that each kernel performs its task as fast as possible. The pipeline uses a brute-force (BF) exhaustive search which in total takes 5 - 24 hours to run depending on the processing cluster architecture. We apply more heuristic, biologically driven genetic algorithms (GAs) to limit the exploration of the total parameter space, tune all four kernels together and reduce the tuning time to few hours. Our results show that after only few hours of tuning, GAs always find similar or even better configurations for all kernels together than the combination of single kernel configurations tuned by the BF approach. At the same time, by means of their genetic operators, GAs converge into better solutions than those obtained by pure random searches. The explored multi-dimensional parameter space is very complex and has multiple local optima as the evolution of randomly generated configurations does not always guarantee global solution.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.04165](https://arxiv.org/abs/1811.04165)

##### PDF
[https://arxiv.org/pdf/1811.04165](https://arxiv.org/pdf/1811.04165)

