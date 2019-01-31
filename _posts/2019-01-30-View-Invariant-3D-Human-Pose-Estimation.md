---
layout: post
title: "View Invariant 3D Human Pose Estimation"
date: 2019-01-30 14:20:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation
author: Guoqiang Wei, Cuiling Lan, Wenjun Zeng, Zhibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The recent success of deep networks has significantly advanced 3D human pose estimation from 2D images. The diversity of capturing viewpoints and the flexibility of the human poses, however, remain some significant challenges. In this paper, we propose a view invariant 3D human pose estimation module to alleviate the effects of viewpoint diversity. The framework consists of a base network, which provides an initial estimation of a 3D pose, a view-invariant hierarchical correction network (VI-HC) on top of that to learn the 3D pose refinement under consistent views, and a view-invariant discriminative network (VID) to enforce high-level constraints over body configurations. In VI-HC, the initial 3D pose inputs are automatically transformed to consistent views for further refinements at the global body and local body parts level, respectively. For the VID, under consistent viewpoints, we use adversarial learning to differentiate between estimated poses and real poses to avoid implausible 3D poses. Experimental results demonstrate that the consistent viewpoints can dramatically enhance the performance. Our module shows robustness for different 3D pose base networks and achieves a significant improvement (about 9%) over a powerful baseline on the public 3D pose estimation benchmark Human3.6M.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10841](http://arxiv.org/abs/1901.10841)

##### PDF
[http://arxiv.org/pdf/1901.10841](http://arxiv.org/pdf/1901.10841)

