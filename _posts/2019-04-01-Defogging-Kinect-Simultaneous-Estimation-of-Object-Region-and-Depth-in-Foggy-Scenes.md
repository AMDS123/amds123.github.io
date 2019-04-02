---
layout: post
title: "Defogging Kinect: Simultaneous Estimation of Object Region and Depth in Foggy Scenes"
date: 2019-04-01 04:35:01
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Yuki Fujimura, Motoharu Sonogashira, Masaaki Iiyama
mathjax: true
---

* content
{:toc}

##### Abstract
Three-dimensional (3D) reconstruction and scene depth estimation from 2-dimensional (2D) images are major tasks in computer vision. However, using conventional 3D reconstruction techniques gets challenging in participating media such as murky water, fog, or smoke. We have developed a method that uses a time-of-flight (ToF) camera to estimate an object region and depth in participating media simultaneously. The scattering component is saturated, so it does not depend on the scene depth, and received signals bouncing off distant points are negligible due to light attenuation in the participating media, so the observation of such a point contains only a scattering component. These phenomena enable us to estimate the scattering component in an object region from a background that only contains the scattering component. The problem is formulated as robust estimation where the object region is regarded as outliers, and it enables the simultaneous estimation of an object region and depth on the basis of an iteratively reweighted least squares (IRLS) optimization scheme. We demonstrate the effectiveness of the proposed method using captured images from a Kinect v2 in real foggy scenes and evaluate the applicability with synthesized data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00558](http://arxiv.org/abs/1904.00558)

##### PDF
[http://arxiv.org/pdf/1904.00558](http://arxiv.org/pdf/1904.00558)

