---
layout: post
title: "Compression and Reconstruction of Random Microstructures using Accelerated Lineal Path Function"
date: 2016-01-17 22:02:54
categories: arXiv_CV
tags: arXiv_CV
author: Jan Havelka, Anna Kučerová, Jan Sýkora
mathjax: true
---

* content
{:toc}

##### Abstract
Microstructure reconstruction and compression techniques are designed to find a microstructure with desired properties. While the microstructure reconstruction searches for a microstructure with prescribed statistical properties, the microstructure compression focuses on efficient representation of material morphology for a purpose of multiscale modelling. Successful application of those techniques, nevertheless, requires proper understanding of underlying statistical descriptors quantifying material morphology. In this paper we focus on the lineal path function designed to capture namely short-range effects and phase connectedness, which can be hardly handled by the commonly used two-point probability function. The usage of the lineal path function is, however, significantly limited by huge computational requirements. So as to examine the properties of the lineal path function within the computationally exhaustive compression and reconstruction processes, we start with the acceleration of the lineal path evaluation, namely by porting part of its code to the graphics processing unit using the CUDA (Compute Unified Device Architecture) programming environment. This allows us to present a unique comparison of the entire lineal path function with the commonly used rough approximation based on the Monte Carlo and/or sampling template. Moreover, the accelerated version of the lineal path function is then compared with the two-point probability function within the compression and reconstruction of two-phase morphologies. Their significant features are thoroughly discussed and illustrated on a set of artificial periodic as well as real-world random microstructures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1601.04359](https://arxiv.org/abs/1601.04359)

##### PDF
[https://arxiv.org/pdf/1601.04359](https://arxiv.org/pdf/1601.04359)

