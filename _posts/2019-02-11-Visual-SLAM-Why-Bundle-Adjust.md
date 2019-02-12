---
layout: post
title: "Visual SLAM: Why Bundle Adjust?"
date: 2019-02-11 06:58:38
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Alvaro Parra Bustos, Tat-Jun Chin, Anders Eriksson, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Bundle adjustment plays a vital role in feature-based monocular SLAM. In many modern SLAM pipelines, bundle adjustment is performed to estimate the 6DOF camera trajectory and 3D map (3D point cloud) from the input feature tracks. However, two fundamental weaknesses plague SLAM systems based on bundle adjustment. First, the need to carefully initialise bundle adjustment means that all variables, in particular the map, must be estimated as accurately as possible and maintained over time, which makes the overall algorithm cumbersome. Second, since estimating the 3D structure (which requires sufficient baseline) is inherent in bundle adjustment, the SLAM algorithm will encounter difficulties during periods of slow motion or pure rotational motion. 
 We propose a different SLAM optimisation core: instead of bundle adjustment, we conduct rotation averaging to incrementally optimise only camera orientations. Given the orientations, we estimate the camera positions and 3D points via a quasi-convex formulation that can be solved efficiently and globally optimally. Our approach not only obviates the need to estimate and maintain the positions and 3D map at keyframe rate (which enables simpler SLAM systems), it is also more capable of handling slow motions or pure rotational motions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03747](http://arxiv.org/abs/1902.03747)

##### PDF
[http://arxiv.org/pdf/1902.03747](http://arxiv.org/pdf/1902.03747)

