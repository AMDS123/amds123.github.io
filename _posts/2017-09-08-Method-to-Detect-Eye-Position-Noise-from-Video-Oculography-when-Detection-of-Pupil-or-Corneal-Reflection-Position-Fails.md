---
layout: post
title: "Method to Detect Eye Position Noise from Video-Oculography when Detection of Pupil or Corneal Reflection Position Fails"
date: 2017-09-08 13:39:14
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Evgeny Abdulin, Lee Friedman, Oleg V. Komogortsev
mathjax: true
---

* content
{:toc}

##### Abstract
We present software to detect noise in eye position signals from video-based eye-tracking systems that depend on accurate pupil and corneal reflection position estimation. When such systems transiently fail to properly detect the pupil or the corneal reflection due to occlusion from eyelids, eye lashes or various shadows, the estimated gaze position is false. This produces an artifactual signal in the position trace that is rapidly, irregularly oscillating between true and false gaze positions. We refer to this noise as RIONEPS (Rapid Irregularly Oscillating Noise of the Eye Position Signal). Our method for detecting these periods automatically is based on an estimate of the relative inefficiency of the eye position signal. We look for RIONEPS in the horizontal and vertical traces separately, and although we typically use it offline, it is suitable to adaptation for real time use. This method requires a threshold to be set, and although we provide some guidance, thresholds will have to be estimated empirically.

##### Abstract (translated by Google)
我们提供软件来检测来自基于视频的眼睛跟踪系统的眼睛位置信号中的噪声，其依赖于准确的瞳孔和角膜反射位置估计。当这样的系统暂时不能正确地检测由于眼睑，眼睫毛或各种阴影的闭塞导致的瞳孔或角膜反射时，估计的注视位置是错误的。这会在位置轨迹上产生真实的信号，在真实和错误的注视位置之间快速地不规则地振荡。我们将这个噪声称为RIONEPS（眼睛位置信号的快速不规则振荡噪声）。我们自动检测这些周期的方法是基于对眼睛位置信号的相对低效率的估计。我们分别在水平和垂直轨迹中寻找RIONEPS，虽然我们通常在离线情况下使用它，但适合实时使用。这个方法需要设定一个门槛，虽然我们提供了一些指导，但是门槛必须经验估计。

##### URL
[https://arxiv.org/abs/1709.02700](https://arxiv.org/abs/1709.02700)

##### PDF
[https://arxiv.org/pdf/1709.02700](https://arxiv.org/pdf/1709.02700)

