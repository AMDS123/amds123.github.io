---
layout: post
title: "Localization of Unmanned Aerial Vehicles in Corridor Environments using Deep Learning"
date: 2019-03-21 14:21:11
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Deep_Learning
author: Ram Prasad Padhy, Shahzad Ahmad, Sachin Verma, Pankaj Kumar Sa, Sambit Bakshi
mathjax: true
---

* content
{:toc}

##### Abstract
Vision-based pose estimation of Unmanned Aerial Vehicles (UAV) in unknown environments is a rapidly growing research area in the field of robot vision. The task becomes more complex when the only available sensor is a static single camera (monocular vision). In this regard, we propose a monocular vision assisted localization algorithm, that will help a UAV to navigate safely in indoor corridor environments. Always, the aim is to navigate the UAV through a corridor in the forward direction by keeping it at the center with no orientation either to the left or right side. The algorithm makes use of the RGB image, captured from the UAV front camera, and passes it through a trained deep neural network (DNN) to predict the position of the UAV as either on the left or center or right side of the corridor. Depending upon the divergence of the UAV with respect to the central bisector line (CBL) of the corridor, a suitable command is generated to bring the UAV to the center. When the UAV is at the center of the corridor, a new image is passed through another trained DNN to predict the orientation of the UAV with respect to the CBL of the corridor. If the UAV is either left or right tilted, an appropriate command is generated to rectify the orientation. We also propose a new corridor dataset, named NITRCorrV1, which contains images as captured by the UAV front camera when the UAV is at all possible locations of a variety of corridors. An exhaustive set of experiments in different corridors reveal the efficacy of the proposed algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09021](http://arxiv.org/abs/1903.09021)

##### PDF
[http://arxiv.org/pdf/1903.09021](http://arxiv.org/pdf/1903.09021)

