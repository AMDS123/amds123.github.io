---
layout: post
title: "Appearance-Based Gaze Estimation via Gaze Decomposition and Single Gaze Point Calibration"
date: 2019-05-11 05:24:48
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Zhaokang Chen, Bertram E. Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Appearance-based gaze estimation provides relatively unconstrained gaze tracking. However, subject-indepen\-dent models achieve limited accuracy partly due to individual variations. To improve estimation, we propose a novel gaze decomposition method and a single gaze point calibration method, motivated by our finding that the inter-subject squared bias exceeds the intra-subject variance for a subject-independent estimator. We decompose the gaze angle into a subject-dependent bias term and a subject-independent difference term between the gaze angle and the bias. The difference term is estimated by a deep convolutional network. For calibration-free tracking, we set the subject-dependent bias term to zero. For single gaze point calibration, we estimate the bias from a few images taken as the subject gazes at a point. Experiments on three datasets indicate that as a calibration-free estimator, the proposed method outperforms the state-of-the-art methods that use single model by up to $10.0\%$. The proposed calibration method is robust and reduces estimation error significantly (up to $35.6\%$), achieving state-of-the-art performance for appearance-based eye trackers with calibration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04451](http://arxiv.org/abs/1905.04451)

##### PDF
[http://arxiv.org/pdf/1905.04451](http://arxiv.org/pdf/1905.04451)

