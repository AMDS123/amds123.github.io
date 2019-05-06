---
layout: post
title: "Do Your Cores Play Nicely? A Portable Framework for Multi-core Interference Tuning and Analysis"
date: 2018-09-13 22:32:34
categories: arXiv_CV
tags: arXiv_CV
author: Dan Iorga, Tyler Sorensen, Alastair F. Donaldson
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-core architectures can be leveraged to allow independent processes to run in parallel. However, due to resources shared across cores, such as caches, distinct processes may interfere with one another, e.g. affecting execution time. Analysing the extent of this interference is difficult due to: (1) the diversity of modern architectures, which may contain different implementations of shared resources, and (2) the complex nature of modern processors, in which interference might arise due to subtle interactions. To address this, we propose a black-box auto-tuning approach that searches for processes that are effective at causing slowdowns for a program when executed in parallel. Such slowdowns provide lower bounds on worst-case execution time; an important metric in systems with real-time constraints. Our approach considers a set of parameterised "enemy" processes and "victim" programs, each targeting a shared resource. The autotuner searches for enemy process parameters that are effective at causing slowdowns in the victim programs. The idea is that victim programs behave as a proxy for shared resource usage of arbitrary programs. We evaluate our approach on: 5 different chips; 3 resources (cache, memory bus, and main memory); and consider several search strategies and slowdown metrics. Using enemy processes tuned per chip, we evaluate the slowdowns on the autobench and coremark benchmark suites and show that our method is able to achieve slowdowns in 98% of benchmark/chip combinations and provide similar results to manually written enemy processes.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.05197](https://arxiv.org/abs/1809.05197)

##### PDF
[https://arxiv.org/pdf/1809.05197](https://arxiv.org/pdf/1809.05197)

