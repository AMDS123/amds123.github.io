---
layout: post
title: "Siamese Convolutional Neural Network for Sub-millimeter-accurate Camera Pose Estimation and Visual Servoing"
date: 2019-03-12 03:39:55
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation CNN
author: Cunjun Yu, Zhongang Cai, Hung Pham, Quang-Cuong Pham
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Servoing (VS), where images taken from a camera typically attached to the robot end-effector are used to guide the robot motions, is an important technique to tackle robotic tasks that require a high level of accuracy. We propose a new neural network, based on a Siamese architecture, for highly accurate camera pose estimation. This, in turn, can be used as a final refinement step following a coarse VS or, if applied in an iterative manner, as a standalone VS on its own. The key feature of our neural network is that it outputs the relative pose between any pair of images, and does so with sub-millimeter accuracy. We show that our network can reduce pose estimation errors to 0.6 mm in translation and 0.4 degrees in rotation, from initial errors of 10 mm / 5 degrees if applied once, or of several cm / tens of degrees if applied iteratively. The network can generalize to similar objects, is robust against changing lighting conditions, and to partial occlusions (when used iteratively). The high accuracy achieved enables tackling low-tolerance assembly tasks downstream: using our network, an industrial robot can achieve 97.5% success rate on a VGA-connector insertion task without any force sensing mechanism.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04713](http://arxiv.org/abs/1903.04713)

##### PDF
[http://arxiv.org/pdf/1903.04713](http://arxiv.org/pdf/1903.04713)

