---
layout: post
title: "Learning to infer: RL-based search for DNN primitive selection on Heterogeneous Embedded Systems"
date: 2018-11-18 11:28:24
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Inference Deep_Learning
author: Miguel de Prado, Nuria Pazos, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning is increasingly being adopted by industry for computer vision applications running on embedded devices. While Convolutional Neural Networks' accuracy has achieved a mature and remarkable state, inference latency and throughput are a major concern especially when targeting low-cost and low-power embedded platforms. CNNs' inference latency may become a bottleneck for Deep Learning adoption by industry, as it is a crucial specification for many real-time processes. Furthermore, deployment of CNNs across heterogeneous platforms presents major compatibility issues due to vendor-specific technology and acceleration libraries. In this work, we present QS-DNN, a fully automatic search based on Reinforcement Learning which, combined with an inference engine optimizer, efficiently explores through the design space and empirically finds the optimal combinations of libraries and primitives to speed up the inference of CNNs on heterogeneous embedded devices. We show that, an optimized combination can achieve 45x speedup in inference latency on CPU compared to a dependency-free baseline and 2x on average on GPGPU compared to the best vendor library. Further, we demonstrate that, the quality of results and time "to-solution" is much better than with Random Search and achieves up to 15x better results for a short-time search.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07315](http://arxiv.org/abs/1811.07315)

##### PDF
[http://arxiv.org/pdf/1811.07315](http://arxiv.org/pdf/1811.07315)

