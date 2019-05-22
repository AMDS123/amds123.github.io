---
layout: post
title: "DNN-Based Multi-Frame MVDR Filtering for Single-Microphone Speech Enhancement"
date: 2019-05-21 08:39:06
categories: arXiv_SD
tags: arXiv_SD Relation
author: Marvin Tammen, D&#xf6;rte Fischer, Simon Doclo
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-frame approaches for single-microphone speech enhancement, e.g., the multi-frame minimum-variance-distortionless-response (MVDR) filter, are able to exploit speech correlations across neighboring time frames. In contrast to single-frame approaches such as the Wiener gain, it has been shown that multi-frame approaches achieve a substantial noise reduction with hardly any speech distortion, provided that an accurate estimate of the correlation matrices and especially the speech interframe correlation vector is available. Typical estimation procedures of the correlation matrices and the speech interframe correlation (IFC) vector require an estimate of the speech presence probability (SPP) in each time-frequency bin. In this paper, we propose to use a bi-directional long short-term memory deep neural network (DNN) to estimate a speech mask and a noise mask for each time-frequency bin, using which two different SPP estimates are derived. Aiming at achieving a robust performance, the DNN is trained for various noise types and signal-to-noise ratios. Experimental results show that the multi-frame MVDR in combination with the proposed data-driven SPP estimator yields an increased speech quality compared to a state-of-the-art model-based estimator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08492](http://arxiv.org/abs/1905.08492)

##### PDF
[http://arxiv.org/pdf/1905.08492](http://arxiv.org/pdf/1905.08492)

