---
layout: post
title: "Automatic Multi-Sensor Extrinsic Calibration for Mobile Robots"
date: 2019-06-11 15:58:07
categories: arXiv_RO
tags: arXiv_RO Optimization
author: David Zu&#xf1;iga-No&#xeb;l, Jose-Raul Ruiz-Sarmiento, Ruben Gomez-Ojeda, Javier Gonzalez-Jimenez
mathjax: true
---

* content
{:toc}

##### Abstract
In order to fuse measurements from multiple sensors mounted on a mobile robot, it is needed to express them in a common reference system through their relative spatial transformations. In this paper, we present a method to estimate the full 6DoF extrinsic calibration parameters of multiple heterogeneous sensors (Lidars, Depth and RGB cameras) suitable for automatic execution on a mobile robot. Our method computes the 2D calibration parameters (x, y, yaw) through a motion-based approach, while for the remaining 3 parameters (z, pitch, roll) it requires the observation of the ground plane for a short period of time. What set this proposal apart from others is that: i) all calibration parameters are initialized in closed form, and ii) the scale ambiguity inherent to motion estimation from a monocular camera is explicitly handled, enabling the combination of these sensors and metric ones (Lidars, stereo rigs, etc.) within the same optimization framework. %Additionally, outlier observations arising from local sensor drift are automatically detected and removed from the calibration process. We provide a formal definition of the problem, as well as of the contributed method, for which a C++ implementation has been made publicly available. The suitability of the method has been assessed in simulation an with real data from indoor and outdoor scenarios. Finally, improvements over state-of-the-art motion-based calibration proposals are shown through experimental evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04670](http://arxiv.org/abs/1906.04670)

##### PDF
[http://arxiv.org/pdf/1906.04670](http://arxiv.org/pdf/1906.04670)

