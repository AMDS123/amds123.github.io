---
layout: post
title: "NTP : A Neural Network Topology Profiler"
date: 2019-05-22 10:55:22
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition Optimization Deep_Learning Recognition
author: Raghavendra Bhat, Pravin Chandran, Juby Jose, Viswanath Dibbur, Prakash Sirra Ajith
mathjax: true
---

* content
{:toc}

##### Abstract
Performance of end-to-end neural networks on a given hardware platform is a function of its compute and memory signature, which in-turn, is governed by a wide range of parameters such as topology size, primitives used, framework used, batching strategy, latency requirements, precision etc. Current benchmarking tools suffer from limitations such as a) being either too granular like DeepBench (or) b) mandate a working implementation that is either framework specific or hardware-architecture specific (or) c) provide only high level benchmark metrics. In this paper, we present NTP (Neural Net Topology Profiler), a sophisticated benchmarking framework, to effectively identify memory and compute signature of an end-to-end topology on multiple hardware architectures, without the need to actually implement the topology in a framework. NTP is tightly integrated with hardware specific benchmark tools to enable exhaustive data collection and analysis. Using NTP, a deep learning researcher can quickly establish baselines needed to understand performance of an end-to-end neural network topology and make high level architectural decisions based on optimization techniques like layer sizing, quantization, pruning etc. Further, integration of NTP with frameworks like Tensorflow, Pytorch, Intel OpenVINO etc. allows for performance comparison along several vectors like a) Comparison of different frameworks on a given hardware b) Comparison of different hardware using a given framework c) Comparison across different heterogeneous hardware configurations for given framework etc. These capabilities empower a researcher to effortlessly make architectural decisions needed for achieving optimized performance on any hardware platform. The paper documents the architectural approach of NTP and demonstrates the capabilities of the tool by benchmarking Mozilla DeepSpeech, a popular Speech Recognition topology.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09063](http://arxiv.org/abs/1905.09063)

##### PDF
[http://arxiv.org/pdf/1905.09063](http://arxiv.org/pdf/1905.09063)

