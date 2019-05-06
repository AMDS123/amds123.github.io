---
layout: post
title: "A GPU implementation of the harmonic sum algorithm"
date: 2018-12-06 16:32:19
categories: arXiv_CV
tags: arXiv_CV
author: Karel Adámek, Wesley Armour
mathjax: true
---

* content
{:toc}

##### Abstract
Time-domain radio astronomy utilizes a harmonic sum algorithm as part of the Fourier domain periodicity search, this type of search is used to discover single pulsars. The harmonic sum algorithm is also used as part of the Fourier domain acceleration search which aims to discover pulsars that are locked in orbit around another pulsar or compact object. However porting the harmonic sum to many-core architectures like GPUs is not a straightforward task. The main problem that must be overcome is the very unfavourable memory access pattern, which gets worse as the dimensionality of the harmonic sum increases. We present a set of algorithms for calculating the harmonic sum that are more suited to many-core architectures such as GPUs. We present an evaluation of the sensitivity of these different approaches, and their performance. This work forms part of the AstroAccelerate project which is a GPU accelerated software package for processing time-domain radio astronomy data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.02647](https://arxiv.org/abs/1812.02647)

##### PDF
[https://arxiv.org/pdf/1812.02647](https://arxiv.org/pdf/1812.02647)

