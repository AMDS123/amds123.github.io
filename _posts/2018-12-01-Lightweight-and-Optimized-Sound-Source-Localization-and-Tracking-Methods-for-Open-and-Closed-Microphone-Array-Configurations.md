---
layout: post
title: "Lightweight and Optimized Sound Source Localization and Tracking Methods for Open and Closed Microphone Array Configurations"
date: 2018-12-01 01:16:06
categories: arXiv_SD
tags: arXiv_SD Tracking
author: Francois Grondin, Francois Michaud
mathjax: true
---

* content
{:toc}

##### Abstract
Human-robot interaction in natural settings requires filtering out the different sources of sounds from the environment. Such ability usually involves the use of microphone arrays to localize, track and separate sound sources online. Multi-microphone signal processing techniques can improve robustness to noise but the processing cost increases with the number of microphones used, limiting response time and widespread use on different types of mobile robots. Since sound source localization methods are the most expensive in terms of computing resources as they involve scanning a large 3D space, minimizing the amount of computations required would facilitate their implementation and use on robots. The robot's shape also brings constraints on the microphone array geometry and configurations. In addition, sound source localization methods usually return noisy features that need to be smoothed and filtered by tracking the sound sources. This paper presents a novel sound source localization method, called SRP-PHAT-HSDA, that scans space with coarse and fine resolution grids to reduce the number of memory lookups. A microphone directivity model is used to reduce the number of directions to scan and ignore non significant pairs of microphones. A configuration method is also introduced to automatically set parameters that are normally empirically tuned according to the shape of the microphone array. For sound source tracking, this paper presents a modified 3D Kalman (M3K) method capable of simultaneously tracking in 3D the directions of sound sources. Using a 16-microphone array and low cost hardware, results show that SRP-PHAT-HSDA and M3K perform at least as well as other sound source localization and tracking methods while using up to 4 and 30 times less computing resources respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00115](http://arxiv.org/abs/1812.00115)

##### PDF
[http://arxiv.org/pdf/1812.00115](http://arxiv.org/pdf/1812.00115)

