---
layout: post
title: "Faint Object Detection in Multi-Epoch Observations via Catalog Data Fusion"
date: 2016-11-10 03:16:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Survey Detection
author: Tamas Budavari, Alexander S. Szalay, Thomas J. Loredo
mathjax: true
---

* content
{:toc}

##### Abstract
Observational astronomy in the time-domain era faces several new challenges. One of them is the efficient use of observations obtained at multiple epochs. The work presented here addresses faint object detection with multi-epoch data, and describes an incremental strategy for separating real objects from artifacts in ongoing surveys, in situations where the single-epoch data are summaries of the full image data, such as single-epoch catalogs of flux and direction estimates for candidate sources. The basic idea is to produce low-threshold single-epoch catalogs, and use a probabilistic approach to accumulate catalog information across epochs; this is in contrast to more conventional strategies based on co-added or stacked image data across all epochs. We adopt a Bayesian approach, addressing object detection by calculating the marginal likelihoods for hypotheses asserting there is no object, or one object, in a small image patch containing at most one cataloged source at each epoch. The object-present hypothesis interprets the sources in a patch at different epochs as arising from a genuine object; the no-object (noise) hypothesis interprets candidate sources as spurious, arising from noise peaks. We study the detection probability for constant-flux objects in a simplified Gaussian noise setting, comparing results based on single exposures and stacked exposures to results based on a series of single-epoch catalog summaries. Computing the detection probability based on catalog data amounts to generalized cross-matching: it is the product of a factor accounting for matching of the estimated fluxes of candidate sources, and a factor accounting for matching of their estimated directions. We find that probabilistic fusion of multi-epoch catalog information can detect sources with only modest sacrifice in sensitivity and selectivity compared to stacking.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.03171](https://arxiv.org/abs/1611.03171)

##### PDF
[https://arxiv.org/pdf/1611.03171](https://arxiv.org/pdf/1611.03171)

