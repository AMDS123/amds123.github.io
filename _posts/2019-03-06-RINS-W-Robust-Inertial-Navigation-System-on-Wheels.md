---
layout: post
title: "RINS-W: Robust Inertial Navigation System on Wheels"
date: 2019-03-06 07:20:02
categories: arXiv_RO
tags: arXiv_RO Object_Detection Knowledge Deep_Learning Detection
author: Martin Brossard (CAOR), Axel Barrau, Silvere Bonnabel (CAOR)
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a real-time approach for long-term inertial navigation based only on an Inertial Measurement Unit (IMU) for self-localizing wheeled robots. The approach builds upon two components: 1) a robust detector that uses recurrent deep neural networks to dynamically detect a variety of situations of interest, such as zero velocity or no lateral slip; and 2) a state-of-the-art Kalman filter which incorporates this knowledge as pseudo-measurements for localization. Evaluations on a publicly available car dataset demonstrates that the proposed scheme may achieve a final precision of 20 m for a 21 km long trajectory of a vehicle driving for over an hour, equipped with an IMU of moderate precision (the gyro drift rate is 10 deg/h). To our knowledge, this is the first paper which combines sophisticated deep learning techniques with state-of-the-art filtering methods for pure inertial navigation on wheeled vehicles and as such opens up for novel data-driven inertial navigation techniques. Moreover, albeit taylored for IMU-only based localization, our method may be used as a component for self-localization of wheeled robots equipped with a more complete sensor suite.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02210](http://arxiv.org/abs/1903.02210)

##### PDF
[http://arxiv.org/pdf/1903.02210](http://arxiv.org/pdf/1903.02210)

