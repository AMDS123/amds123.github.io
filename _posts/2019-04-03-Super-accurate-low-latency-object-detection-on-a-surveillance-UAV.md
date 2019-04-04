---
layout: post
title: "Super accurate low latency object detection on a surveillance UAV"
date: 2019-04-03 14:29:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Drone Object_Tracking Optimization Detection
author: Maarten Vandersteegen, Kristof Vanbeeck, Toon goedeme
mathjax: true
---

* content
{:toc}

##### Abstract
Drones have proven to be useful in many industry segments such as security and surveillance, where e.g. on-board real-time object tracking is a necessity for autonomous flying guards. Tracking and following suspicious objects is therefore required in real-time on limited hardware. With an object detector in the loop, low latency becomes extremely important. In this paper, we propose a solution to make object detection for UAVs both fast and super accurate. We propose a multi-dataset learning strategy yielding top eye-sky object detection accuracy. Our model generalizes well on unseen data and can cope with different flying heights, optically zoomed-in shots and different viewing angles. We apply optimization steps such that we achieve minimal latency on embedded on-board hardware by fusing layers, quantizing calculations to 16-bit floats and 8-bit integers, with negligible loss in accuracy. We validate on NVIDIA's Jetson TX2 and Jetson Xavier platforms where we achieve a speed-wise performance boost of more than 10x.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02024](https://arxiv.org/abs/1904.02024)

##### PDF
[https://arxiv.org/pdf/1904.02024](https://arxiv.org/pdf/1904.02024)

