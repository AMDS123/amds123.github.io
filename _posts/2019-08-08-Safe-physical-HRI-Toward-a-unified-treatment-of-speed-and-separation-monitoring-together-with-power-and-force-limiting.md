---
layout: post
title: "Safe physical HRI: Toward a unified treatment of speed and separation monitoring together with power and force limiting"
date: 2019-08-08 12:58:33
categories: arXiv_RO
tags: arXiv_RO Face Pose_Estimation
author: Petr Svarny, Michael Tesar, Jan Kristof Behrens, Matej Hoffmann
mathjax: true
---

* content
{:toc}

##### Abstract
So-called collaborative robots are a current trend in industrial robotics. However, they still face many problems in practical application such as reduced speed to ascertain their collaborativeness. The standards prescribe two regimes: (i) speed and separation monitoring and (ii) power and force limiting, where the former requires reliable estimation of distances between the robot and human body parts and the latter imposes constraints on the energy absorbed during collisions prior to robot stopping. Following the standards, we deploy the two collaborative regimes in a single application and study the performance in a mock collaborative task under the individual regimes, including transitions between them. Additionally, we compare the performance under "safety zone monitoring" with keypoint pair-wise separation distance assessment relying on an RGB-D sensor and skeleton extraction algorithm to track human body parts in the workspace. Best performance has been achieved in the following setting: robot operates at full speed until a distance threshold between any robot and human body part is crossed; then, reduced robot speed per power and force limiting is triggered. Robot is halted only when the operator's head crosses a predefined distance from selected robot parts. We demonstrate our methodology on a setup combining a KUKA LBR iiwa robot, Intel RealSense RGB-D sensor and OpenPose for human pose estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03046](http://arxiv.org/abs/1908.03046)

##### PDF
[http://arxiv.org/pdf/1908.03046](http://arxiv.org/pdf/1908.03046)

