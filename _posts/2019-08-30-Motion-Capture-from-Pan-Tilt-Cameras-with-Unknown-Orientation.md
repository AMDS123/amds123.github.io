---
layout: post
title: "Motion Capture from Pan-Tilt Cameras with Unknown Orientation"
date: 2019-08-30 12:12:54
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Roman Bachmann, J&#xf6;rg Sp&#xf6;rri, Pascal Fua, Helge Rhodin
mathjax: true
---

* content
{:toc}

##### Abstract
In sports, such as alpine skiing, coaches would like to know the speed and various biomechanical variables of their athletes and competitors. Existing methods use either body-worn sensors, which are cumbersome to setup, or manual image annotation, which is time consuming. We propose a method for estimating an athlete's global 3D position and articulated pose using multiple cameras. By contrast to classical markerless motion capture solutions, we allow cameras to rotate freely so that large capture volumes can be covered. In a first step, tight crops around the skier are predicted and fed to a 2D pose estimator network. The 3D pose is then reconstructed using a bundle adjustment method. Key to our solution is the rotation estimation of Pan-Tilt cameras in a joint optimization with the athlete pose and conditioning on relative background motion computed with feature tracking. Furthermore, we created a new alpine skiing dataset and annotated it with 2D pose labels, to overcome shortcomings of existing ones. Our method estimates accurate global 3D poses from images only and provides coaches with an automatic and fast tool for measuring and improving an athlete's performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11676](http://arxiv.org/abs/1908.11676)

##### PDF
[http://arxiv.org/pdf/1908.11676](http://arxiv.org/pdf/1908.11676)

