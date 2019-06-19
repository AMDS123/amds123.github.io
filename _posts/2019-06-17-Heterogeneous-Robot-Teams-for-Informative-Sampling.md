---
layout: post
title: "Heterogeneous Robot Teams for Informative Sampling"
date: 2019-06-17 18:16:14
categories: arXiv_RO
tags: arXiv_RO Survey
author: Travis Manderson, Sandeep Manjanna, Gregory Dudek
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a cooperative multi-robot strategy to adaptively explore and sample environments that are unfavorable for humans. We propose a methodology for a team of heterogeneous robots to collaborate on information based planning for applications like sampling thermal imagery in a wildfire affected site to assist with detecting spot fires and areas of residual fires, fire mapping and monitoring fire progression or applications in marine domain for coral reef monitoring and survey. We use Gabor filter based texture classifier on aerial images from an Unmanned Aerial Vehicle (UAV) to segment the region of interest into classes. A policy gradient based path planner is used on the texture classified aerial image to plan a path for the Unmanned Ground Vehicle (UGV). The UGV then uses a local planner to reach the goals set by the global planner by avoiding obstacles. The UGV also learns the labels for the segmented classes as drivable and non-drivable using the feedback from the performance while reaching the planned waypoints. We evaluated the building blocks of our approach and present the results with application of these strategies to different domains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07208](http://arxiv.org/abs/1906.07208)

##### PDF
[http://arxiv.org/pdf/1906.07208](http://arxiv.org/pdf/1906.07208)

