---
layout: post
title: "A Distributed Approach to LARS Stream Reasoning"
date: 2019-07-29 11:39:05
categories: arXiv_AI
tags: arXiv_AI
author: Thomas Eiter, Paul Ogris, Konstantin Schekotihin
mathjax: true
---

* content
{:toc}

##### Abstract
Stream reasoning systems are designed for complex decision-making from possibly infinite, dynamic streams of data. Modern approaches to stream reasoning are usually performing their computations using stand-alone solvers, which incrementally update their internal state and return results as the new portions of data streams are pushed. However, the performance of such approaches degrades quickly as the rates of the input data and the complexity of decision problems are growing. This problem was already recognized in the area of stream processing, where systems became distributed in order to allocate vast computing resources provided by clouds. In this paper we propose a distributed approach to stream reasoning that can efficiently split computations among different solvers communicating their results over data streams. Moreover, in order to increase the throughput of the distributed system, we suggest an interval-based semantics for the LARS language, which enables significant reductions of network traffic. Performed evaluations indicate that the distributed stream reasoning significantly outperforms existing stand-alone LARS solvers when the complexity of decision problems and the rate of incoming data are increasing. Under consideration for acceptance in Theory and Practice of Logic Programming.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12344](http://arxiv.org/abs/1907.12344)

##### PDF
[http://arxiv.org/pdf/1907.12344](http://arxiv.org/pdf/1907.12344)

