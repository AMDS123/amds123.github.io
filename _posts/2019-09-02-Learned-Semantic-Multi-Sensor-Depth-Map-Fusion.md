---
layout: post
title: "Learned Semantic Multi-Sensor Depth Map Fusion"
date: 2019-09-02 13:15:24
categories: arXiv_CV
tags: arXiv_CV Face
author: Denys Rozumnyi, Ian Cherabier, Marc Pollefeys, Martin R. Oswald
mathjax: true
---

* content
{:toc}

##### Abstract
Volumetric depth map fusion based on truncated signed distance functions has become a standard method and is used in many 3D reconstruction pipelines. In this paper, we are generalizing this classic method in multiple ways: 1) Semantics: Semantic information enriches the scene representation and is incorporated into the fusion process. 2) Multi-Sensor: Depth information can originate from different sensors or algorithms with very different noise and outlier statistics which are considered during data fusion. 3) Scene denoising and completion: Sensors can fail to recover depth for certain materials and light conditions, or data is missing due to occlusions. Our method denoises the geometry, closes holes and computes a watertight surface for every semantic class. 4) Learning: We propose a neural network reconstruction method that unifies all these properties within a single powerful framework. Our method learns sensor or algorithm properties jointly with semantic depth fusion and scene completion and can also be used as an expert system, e.g. to unify the strengths of various photometric stereo algorithms. Our approach is the first to unify all these properties. Experimental evaluations on both synthetic and real data sets demonstrate clear improvements.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00703](http://arxiv.org/abs/1909.00703)

##### PDF
[http://arxiv.org/pdf/1909.00703](http://arxiv.org/pdf/1909.00703)

