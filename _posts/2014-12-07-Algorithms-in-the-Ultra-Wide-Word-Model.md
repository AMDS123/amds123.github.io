---
layout: post
title: "Algorithms in the Ultra-Wide Word Model"
date: 2014-12-07 17:36:42
categories: arXiv_CV
tags: arXiv_CV
author: Arash Farzan, Alejandro López-Ortiz, Patrick K. Nicholson, Alejandro Salinger
mathjax: true
---

* content
{:toc}

##### Abstract
The effective use of parallel computing resources to speed up algorithms in current multi-core parallel architectures remains a difficult challenge, with ease of programming playing a key role in the eventual success of various parallel architectures. In this paper we consider an alternative view of parallelism in the form of an ultra-wide word processor. We introduce the Ultra-Wide Word architecture and model, an extension of the word-RAM model that allows for constant time operations on thousands of bits in parallel. Word parallelism as exploited by the word-RAM model does not suffer from the more difficult aspects of parallel programming, namely synchronization and concurrency. For the standard word-RAM algorithms, the speedups obtained are moderate, as they are limited by the word size. We argue that a large class of word-RAM algorithms can be implemented in the Ultra-Wide Word model, obtaining speedups comparable to multi-threaded computations while keeping the simplicity of programming of the sequential RAM model. We show that this is the case by describing implementations of Ultra-Wide Word algorithms for dynamic programming and string searching. In addition, we show that the Ultra-Wide Word model can be used to implement a nonstandard memory architecture, which enables the sidestepping of lower bounds of important data structure problems such as priority queues and dynamic prefix sums. While similar ideas about operating on large words have been mentioned before in the context of multimedia processors [Thorup 2003], it is only recently that an architecture like the one we propose has become feasible and that details can be worked out.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1411.7359](https://arxiv.org/abs/1411.7359)

##### PDF
[https://arxiv.org/pdf/1411.7359](https://arxiv.org/pdf/1411.7359)

