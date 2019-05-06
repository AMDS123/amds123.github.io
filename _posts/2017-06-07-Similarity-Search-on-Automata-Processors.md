---
layout: post
title: "Similarity Search on Automata Processors"
date: 2017-06-07 18:53:02
categories: arXiv_CV
tags: arXiv_CV Optimization Recommendation
author: Vincent T. Lee, Justin Kotalik, Carlo C. Del Mundo, Armin Alaghi, Luis Ceze, Mark Oskin
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity search is a critical primitive for a wide variety of applications including natural language processing, content-based search, machine learning, computer vision, databases, robotics, and recommendation systems. At its core, similarity search is implemented using the k-nearest neighbors (kNN) algorithm, where computation consists of highly parallel distance calculations and a global top-k sort. In contemporary von-Neumann architectures, kNN is bottlenecked by data movement which limits throughput and latency. In this paper, we present and evaluate a novel automata-based algorithm for kNN on the Micron Automata Processor (AP), which is a non-von Neumann near-data processing architecture. By employing near-data processing, the AP minimizes the data movement bottleneck and is able to achieve better performance. Unlike prior work in the automata processing space, our work combines temporal encodings with automata design to augment the space of applications for the AP. We evaluate our design's performance on the AP and compare to state-of-the-art CPU, GPU, and FPGA implementations; we show that the current generation of AP hardware can achieve over 50x speedup over CPUs while maintaining competitive energy efficiency gains. We also propose several automata optimization techniques and simple architectural extensions that highlight the potential of the AP hardware.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1608.03175](https://arxiv.org/abs/1608.03175)

##### PDF
[https://arxiv.org/pdf/1608.03175](https://arxiv.org/pdf/1608.03175)

