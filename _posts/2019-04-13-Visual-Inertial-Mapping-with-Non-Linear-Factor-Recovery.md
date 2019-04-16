---
layout: post
title: "Visual-Inertial Mapping with Non-Linear Factor Recovery"
date: 2019-04-13 08:15:00
categories: arXiv_CV
tags: arXiv_CV
author: Vladyslav Usenko, Nikolaus Demmel, David Schubert, J&#xf6;rg St&#xfc;ckler, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Cameras and inertial measurement units are complementary sensors for ego-motion estimation and environment mapping. Their combination makes visual-inertial odometry (VIO) systems more accurate and robust. For globally consistent mapping, however, combining visual and inertial information is not straightforward. To estimate the motion and geometry with a set of images large baselines are required. Because of that, most systems operate on keyframes that have large time intervals between each other. Inertial data on the other hand quickly degrades with the duration of the intervals and after several seconds of integration, it typically contains only little useful information. 
 In this paper, we propose to extract relevant information for visual-inertial mapping from visual-inertial odometry using non-linear factor recovery. We reconstruct a set of non-linear factors that make an optimal approximation of the information on the trajectory accumulated by VIO. To obtain a globally consistent map we combine these factors with loop-closing constraints using bundle adjustment. The VIO factors make the roll and pitch angles of the global map observable, and improve the robustness and the accuracy of the mapping. In experiments on a public benchmark, we demonstrate superior performance of our method over the state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06504](http://arxiv.org/abs/1904.06504)

##### PDF
[http://arxiv.org/pdf/1904.06504](http://arxiv.org/pdf/1904.06504)

