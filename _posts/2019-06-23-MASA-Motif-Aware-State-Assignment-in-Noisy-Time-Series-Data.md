---
layout: post
title: "MASA: Motif-Aware State Assignment in Noisy Time Series Data"
date: 2019-06-23 00:24:56
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Saachi Jain, David Hallac, Rok Sosic, Jure Leskovec
mathjax: true
---

* content
{:toc}

##### Abstract
Complex systems, such as airplanes, cars, or financial markets, produce multivariate time series data consisting of a large number of system measurements over a period of time. Such data can be interpreted as a sequence of states, where each state represents a prototype of system behavior. An important problem in this domain is to identify repeated sequences of states, known as motifs. Such motifs correspond to complex behaviors that capture common sequences of state transitions. For example, in automotive data, a motif of "making a turn" might manifest as a sequence of states: slowing down, turning the wheel, and then speeding back up. However, discovering these motifs is challenging, because the individual states and state assignments are unknown, have different durations, and need to be jointly learned from the noisy time series. Here we develop motif-aware state assignment (MASA), a method to discover common motifs in noisy time series data and leverage those motifs to more robustly assign states to measurements. We formulate the problem of motif discovery as a large optimization problem, which we solve using an expectation-maximization type approach. MASA performs well in the presence of noise in the input data and is scalable to very large datasets. Experiments on synthetic data show that MASA outperforms state-of-the-art baselines by up to 38.2%, and two case studies demonstrate how our approach discovers insightful motifs in the presence of noise in real-world time series data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.01819](http://arxiv.org/abs/1809.01819)

##### PDF
[http://arxiv.org/pdf/1809.01819](http://arxiv.org/pdf/1809.01819)

