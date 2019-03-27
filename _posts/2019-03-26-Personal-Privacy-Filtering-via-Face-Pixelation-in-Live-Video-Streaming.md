---
layout: post
title: "Personal Privacy Filtering via Face Pixelation in Live Video Streaming"
date: 2019-03-26 12:38:45
categories: arXiv_CV
tags: arXiv_CV GAN Face Detection Face_Detection Recognition
author: Jizhe Zhou, Chi-Man Pun, YingYu Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Face pixelation in TV shows or videos is manually realized and not well studied to date. As the prevailing of online video streaming, we develop a new tool called face pixelation in live-streaming (FPLV) to generate automatic personal privacy filtering during unconstrained streaming. FPLV is organized in a frame-to-video structure for fast and accurate face pixelation of irrelevant people. Leveraging image-based face detection and recognition networks on individual frames, we propose a positioned incremental affinity propagation (PIAP) clustering algorithm to associate faces across frames. Through deep feature and position aggregated affinities, PIAP handles the cluster number generation, new cluster discovering, and faces' raw trajectories forming simultaneously. Affected by various factors, raw trajectories might be intermittent and unreliable. Hence, we introduce a proposal net for loosed face detection with an empirical likelihood test to compensate the deep network insufficiency and refine the raw trajectories. A Gaussian filter is laid on refined trajectories for final pixelation. FPLV obtains satisfying accuracy and real-time performances under streaming video data we collected.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10836](http://arxiv.org/abs/1903.10836)

##### PDF
[http://arxiv.org/pdf/1903.10836](http://arxiv.org/pdf/1903.10836)

