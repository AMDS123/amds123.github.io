---
layout: post
title: "FastCal: Robust Online Self-Calibration for Robotic Systems"
date: 2019-02-27 15:26:48
categories: arXiv_RO
tags: arXiv_RO
author: Fernando Nobre, Christoffer Heckman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a solution for sensor extrinsic self-calibration with very low time complexity, competitive accuracy and graceful handling of often-avoided corner cases: drift in calibration parameters and unobservable directions in the parameter space. It consists of three main parts: 1) information-theoretic based segment selection for constant-time estimation; 2) observability-aware parameter update through a rank-revealing decomposition of the Fisher information matrix; 3) drift-correcting self-calibration through the time-decay of segments. At the core of our FastCal algorithm is the loosely-coupled formulation for sensor extrinsics calibration and efficient selection of measurements. FastCal runs up to an order of magnitude faster than similar self-calibration algorithms (camera-to-camera extrinsics, excluding feature-matching and image pre-processing on all comparisons), making FastCal ideal for integration into existing, resource-constrained, robotics systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10585](http://arxiv.org/abs/1902.10585)

##### PDF
[http://arxiv.org/pdf/1902.10585](http://arxiv.org/pdf/1902.10585)

