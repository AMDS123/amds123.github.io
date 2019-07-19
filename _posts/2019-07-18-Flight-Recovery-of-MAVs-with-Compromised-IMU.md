---
layout: post
title: "Flight Recovery of MAVs with Compromised IMU"
date: 2019-07-18 14:34:33
categories: arXiv_RO
tags: arXiv_RO Adversarial Detection
author: Zhan Tu, Fan Fei, Matthew Eagon, Dongyan Xu, Xinyan Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Micro Aerial Vehicles (MAVs) rely on onboard attitude and position sensors for autonomous flight. Due to their size, weight, and power (SWaP) constraints, most modern MAVs use miniaturized inertial measurement units (IMUs) to provide attitude feedback, which is critical for flight stabilization and control. However, recent adversarial attack studies have demonstrated that many commonly used IMUs are vulnerable to attacks exploiting their physical characteristics. Conventional redundancy-based approaches are not effective against such attacks because redundant IMUs have the same or similar physical vulnerabilities. In this paper, we present a novel fault-tolerant solution for IMU compromised scenarios, using separate position and heading information to restore the failed attitude states. Rather than adding more IMU alternatives for recovery, the proposed method is intended to minimize any modifications to the existing system and control program. Thus, it is particularly useful for vehicles that have tight SWaP constraints while requiring simultaneous high performance and safety demands. To execute the recovery logic properly, a robust estimator was designed for fine-grained detection and isolation of the faulty sensors. The effectiveness of the proposed approach was validated on a quadcopter MAV through both simulation and experimental flight tests.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00063](http://arxiv.org/abs/1812.00063)

##### PDF
[http://arxiv.org/pdf/1812.00063](http://arxiv.org/pdf/1812.00063)

