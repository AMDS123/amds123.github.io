---
layout: post
title: "Slim DensePose: Thrifty Learning from Sparse Annotations and Motion Cues"
date: 2019-06-13 14:07:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Pose_Estimation Detection
author: Natalia Neverova, James Thewlis, Rıza Alp Güler, Iasonas Kokkinos, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
DensePose supersedes traditional landmark detectors by densely mapping image pixels to body surface coordinates. This power, however, comes at a greatly increased annotation time, as supervising the model requires to manually label hundreds of points per pose instance. In this work, we thus seek methods to significantly slim down the DensePose annotations, proposing more efficient data collection strategies. In particular, we demonstrate that if annotations are collected in video frames, their efficacy can be multiplied for free by using motion cues. To explore this idea, we introduce DensePose-Track, a dataset of videos where selected frames are annotated in the traditional DensePose manner. Then, building on geometric properties of the DensePose mapping, we use the video dynamic to propagate ground-truth annotations in time as well as to learn from Siamese equivariance constraints. Having performed exhaustive empirical evaluation of various data annotation and learning strategies, we demonstrate that doing so can deliver significantly improved pose estimation results over strong baselines. However, despite what is suggested by some recent works, we show that merely synthesizing motion patterns by applying geometric transformations to isolated frames is significantly less effective, and that motion cues help much more when they are extracted from videos.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05706](https://arxiv.org/abs/1906.05706)

##### PDF
[https://arxiv.org/pdf/1906.05706](https://arxiv.org/pdf/1906.05706)

