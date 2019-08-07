---
layout: post
title: "Live Illumination Decomposition of Videos"
date: 2019-08-06 05:23:45
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Quantitative
author: Abhimitra Meka, Mohammad Shafiei, Michael Zollhoefer, Christian Richardt, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the first approach for the decomposition of a monocular color video into direct and indirect illumination components in real-time. We retrieve, in separate layers, the contribution made to the scene appearance by the scene reflectance, the light sources and the reflections from various coherent scene regions to one another. Existing techniques that invert global light transport require image capture under multiplexed controlled lighting, or only enable the decomposition of a single image at slow off-line frame rates. In contrast, our approach works for regular videos and produces temporally coherent decomposition layers at real-time frame rates. At the core of our approach are several sparsity priors that enable the estimation of the per-pixel direct and indirect illumination layers based on a small set of jointly estimated base reflectance colors. The resulting variational decomposition problem uses a new formulation based on sparse and dense sets of non-linear equations that we solve efficiently using a novel alternating data-parallel optimization strategy. We evaluate our approach qualitatively and quantitatively, and show improvements over the state of the art in this field, in both quality and runtime. In addition, we demonstrate various real-time appearance editing applications for videos with consistent illumination.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01961](http://arxiv.org/abs/1908.01961)

##### PDF
[http://arxiv.org/pdf/1908.01961](http://arxiv.org/pdf/1908.01961)

