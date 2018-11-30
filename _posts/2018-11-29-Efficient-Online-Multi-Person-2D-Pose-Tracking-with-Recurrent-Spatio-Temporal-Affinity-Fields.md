---
layout: post
title: "Efficient Online Multi-Person 2D Pose Tracking with Recurrent Spatio-Temporal Affinity Fields"
date: 2018-11-29 05:57:53
categories: arXiv_CV
tags: arXiv_CV Tracking Inference
author: Yaadhav Raaj, Haroon Idrees, Gines Hidalgo, Yaser Sheikh
mathjax: true
---

* content
{:toc}

##### Abstract
We present an online approach to efficiently and simultaneously detect and track the 2D pose of multiple people in a video sequence. We build upon Part Affinity Field (PAF) representation designed for static images, and propose an architecture that can encode and predict Spatio-Temporal Affinity Fields (STAF) across a video sequence. In particular, we propose a novel temporal topology cross-linked across limbs which can consistently handle body motions of a wide range of magnitudes. Additionally, we make the overall approach recurrent in nature, where the network ingests STAF heatmaps from previous frames and estimates those for the current frame. Our approach uses only online inference and tracking, and is currently the fastest and the most accurate bottom-up approach that is runtime invariant to the number of people in the scene and accuracy invariant to input frame rate of camera. Running at $\sim$30 fps on a single GPU at single scale, it achieves highly competitive results on the PoseTrack benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11975](http://arxiv.org/abs/1811.11975)

##### PDF
[http://arxiv.org/pdf/1811.11975](http://arxiv.org/pdf/1811.11975)

