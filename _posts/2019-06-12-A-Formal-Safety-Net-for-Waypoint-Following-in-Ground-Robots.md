---
layout: post
title: "A Formal Safety Net for Waypoint Following in Ground Robots"
date: 2019-06-12 18:19:24
categories: arXiv_RO
tags: arXiv_RO
author: Brandon Bohrer, Yong Kiam Tan, Stefan Mitsch, Andrew Sogokon, Andr&#xe9; Platzer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a reusable formally verified safety net that provides end-to-end safety and liveness guarantees for 2D waypoint-following of Dubins-type ground robots with tolerances and acceleration. We: i) Model a robot in differential dynamic logic (dL), and specify assumptions on the controller and robot kinematics, ii) Prove formal safety and liveness properties for waypoint-following with speed limits, iii) Synthesize a monitor, which is automatically proven to enforce model compliance at runtime, and iv) Our use of the VeriPhy toolchain makes these guarantees carry over down to the level of machine code with untrusted controllers, environments, and plans. The guarantees for the safety net apply to any robot as long as the waypoints are chosen safely and the physical assumptions in its model hold. Experiments show these assumptions hold in practice, with an inherent trade-off between compliance and performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05073](http://arxiv.org/abs/1903.05073)

##### PDF
[http://arxiv.org/pdf/1903.05073](http://arxiv.org/pdf/1903.05073)

