---
layout: post
title: "Recognizing and Tracking High-Level, Human-Meaningful Navigation Features of Occupancy Grid Maps"
date: 2019-03-08 21:07:10
categories: arXiv_RO
tags: arXiv_RO Tracking CNN Detection SLAM
author: Payam Nikdel, Richard Vaughan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a system whereby a robot detects and track human-meaningful navigational cues as it navigates in an indoor environment. It is intended as the sensor front-end for a mobile robot system that can communicate its navigational context with human users. From simulated LiDAR scan data we construct a set of 2D occupancy grid bitmaps, then hand-label these with human-scale navigational features such as closed doors, open corridors and intersections. We train a Convolutional Neural Network (CNN) to recognize these features on input bitmaps. In our demonstration system, these features are detected at every time step then passed to a tracking module that does frame-to-frame data association to improve detection accuracy and identify stable unique features. We evaluate the system in both simulation and the real world. We compare the performance of using input occupancy grids obtained directly from LiDAR data, or incrementally constructed with SLAM, and their combination.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03669](https://arxiv.org/abs/1903.03669)

##### PDF
[https://arxiv.org/pdf/1903.03669](https://arxiv.org/pdf/1903.03669)

