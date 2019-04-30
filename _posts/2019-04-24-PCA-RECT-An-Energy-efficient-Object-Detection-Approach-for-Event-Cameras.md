---
layout: post
title: "PCA-RECT: An Energy-efficient Object Detection Approach for Event Cameras"
date: 2019-04-24 09:11:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Classification Detection Recognition
author: Bharath Ramesh, Andres Ussa, Luca Della Vedova, Hong Yang, Garrick Orchard
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first purely event-based, energy-efficient approach for object detection and categorization using an event camera. Compared to traditional frame-based cameras, choosing event cameras results in high temporal resolution (order of microseconds), low power consumption (few hundred mW) and wide dynamic range (120 dB) as attractive properties. However, event-based object recognition systems are far behind their frame-based counterparts in terms of accuracy. To this end, this paper presents an event-based feature extraction method devised by accumulating local activity across the image frame and then applying principal component analysis (PCA) to the normalized neighborhood region. Subsequently, we propose a backtracking-free k-d tree mechanism for efficient feature matching by taking advantage of the low-dimensionality of the feature representation. Additionally, the proposed k-d tree mechanism allows for feature selection to obtain a lower-dimensional dictionary representation when hardware resources are limited to implement dimensionality reduction. Consequently, the proposed system can be realized on a field-programmable gate array (FPGA) device leading to high performance over resource ratio. The proposed system is tested on real-world event-based datasets for object categorization, showing superior classification performance and relevance to state-of-the-art algorithms. Additionally, we verified the object detection method and real-time FPGA performance in lab settings under non-controlled illumination conditions with limited training data and ground truth annotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12665](http://arxiv.org/abs/1904.12665)

##### PDF
[http://arxiv.org/pdf/1904.12665](http://arxiv.org/pdf/1904.12665)

