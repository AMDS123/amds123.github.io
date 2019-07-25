---
layout: post
title: "Efficient Circle-Based Camera Pose Tracking Free of PnP"
date: 2019-07-24 03:07:45
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Fulin Tang, Yihong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Camera pose tracking attracts much interest both from academic and industrial communities, of which the methods based on planar markers are easy to be implemented. However, most of the existing methods need to identify multiple points in the marker images for matching to space points. Then, PnP and RANSAC are used to compute the camera pose. If cameras move fast or are far away from markers, matching is easy to generate errors and even RANSAC cannot remove incorrect matching. Then, the result by PnP cannot have good performance. To solve this problem, we design circular markers and represent 6D camera pose analytically and unifiedly as very concise forms from each of the marker by projective invariance. Afterwards, the pose is further optimized by a proposed nonlinear cost function based on a polar-n-direction geometric distance. The method is from imaged circle edges and without PnP/RANSAC, making pose tracking robust and accurate. Experimental results show that the proposed method outperforms the state of the arts in terms of noise, blur, and distance from camera to marker. Simultaneously, it can still run at about 100 FPS on a consumer computer with only CPU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10219](http://arxiv.org/abs/1907.10219)

##### PDF
[http://arxiv.org/pdf/1907.10219](http://arxiv.org/pdf/1907.10219)

