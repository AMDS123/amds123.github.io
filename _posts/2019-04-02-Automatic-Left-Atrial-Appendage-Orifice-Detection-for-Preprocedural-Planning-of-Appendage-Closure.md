---
layout: post
title: "Automatic Left Atrial Appendage Orifice Detection for Preprocedural Planning of Appendage Closure"
date: 2019-04-02 06:56:11
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning Detection
author: Walid Abdullah Al, Il Dong Yun, Eun Ju Chun
mathjax: true
---

* content
{:toc}

##### Abstract
In preoperative planning of left atrial appendage closure (LAAC) with CT angiography, the assessment of the appendage orifice plays a crucial role in choosing an appropriate LAAC device size and a proper C-arm angulation. However, accurate orifice detection is laborious because of the high anatomic variation of the appendage, as well as the unclear orifice position and orientation in the available views. We propose an automatic orifice detection approach performing a search on the principal medial axis of the appendage, where we present an efficient iterative algorithm to grow the axis from the appendage to the left atrium. We propose to use the axis-to-surface distance of the appendage for efficient and effective detection. To localize the necessary initial seed for growing the medial axis, we train an artificial localization agent using an actor-critic reinforcement learning approach, defining the localization as a sequential decision process. The entire detection process takes only about 8 seconds, and the variance of the detected orifice with respect to annotations from two experts is calculated to be significantly small and less than the inter-observer variance. The proposed orifice search on the medial axis of the appendage comparing only its distance from the surface provides a simple, yet robust solution for orifice detection. While being the first fully automatic approach and providing a detection error below the inter-observer difference, our method improved the detection efficiency by eighteen times compared to the existing solution, therefore, can be potentially useful for physicians.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01241](http://arxiv.org/abs/1904.01241)

##### PDF
[http://arxiv.org/pdf/1904.01241](http://arxiv.org/pdf/1904.01241)

