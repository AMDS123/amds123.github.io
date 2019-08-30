---
layout: post
title: "Enabling Simulation-Based Optimization Through Machine Learning: A Case Study on Antenna Design"
date: 2019-08-29 13:43:11
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Paolo Testolina, Mattia Lecci, Mattia Rebato, Alberto Testolin, Jonathan Gambini, Roberto Flamini, Christian Mazzucco, Michele Zorzi
mathjax: true
---

* content
{:toc}

##### Abstract
Complex phenomena are generally modeled with sophisticated simulators that, depending on their accuracy, can be very demanding in terms of computational resources and simulation time. Their time-consuming nature, together with a typically vast parameter space to be explored, make simulation-based optimization often infeasible. In this work, we present a method that enables the optimization of complex systems through Machine Learning (ML) techniques. We show how well-known learning algorithms are able to reliably emulate a complex simulator with a modest dataset obtained from it. The trained emulator is then able to yield values close to the simulated ones in virtually no time. Therefore, it is possible to perform a global numerical optimization over the vast multi-dimensional parameter space, in a fraction of the time that would be required by a simple brute-force search. As a testbed for the proposed methodology, we used a network simulator for next-generation mmWave cellular systems. After simulating several antenna configurations and collecting the resulting network-level statistics, we feed it into our framework. Results show that, even with few data points, extrapolating a continuous model makes it possible to estimate the global optimum configuration almost instantaneously. The very same tool can then be used to achieve any further optimization goal on the same input parameters in negligible time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11225](http://arxiv.org/abs/1908.11225)

##### PDF
[http://arxiv.org/pdf/1908.11225](http://arxiv.org/pdf/1908.11225)

