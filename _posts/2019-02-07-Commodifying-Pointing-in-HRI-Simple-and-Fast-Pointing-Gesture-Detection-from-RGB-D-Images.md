---
layout: post
title: "Commodifying Pointing in HRI: Simple and Fast Pointing Gesture Detection from RGB-D Images"
date: 2019-02-07 14:28:13
categories: arXiv_RO
tags: arXiv_RO Object_Detection Face Detection
author: Bita Azari, Angelica Lim, Richard T. Vaughan
mathjax: true
---

* content
{:toc}

##### Abstract
We present and characterize a simple method for detecting pointing gestures suitable for human-robot interaction applications using a commodity RGB-D camera. We exploit a state-of-the-art Deep CNN-based detector to find hands and faces in RGB images, then examine the corresponding depth channel pixels to obtain full 3D pointing vectors. We test several methods of estimating the hand end-point of the pointing vector. The system runs at better than 30Hz on commodity hardware: exceeding the frame rate of typical RGB-D sensors. An estimate of the absolute pointing accuracy is found empirically by comparison with ground-truth data from a VICON motion-capture system, and the useful interaction volume established. Finally, we show an end-to-end test where a robot estimates where the pointing vector intersects the ground plane, and report the accuracy obtained. We provide source code as a ROS node, with the intention of contributing a commodity implementation of this common component in HRI systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02636](http://arxiv.org/abs/1902.02636)

##### PDF
[http://arxiv.org/pdf/1902.02636](http://arxiv.org/pdf/1902.02636)

