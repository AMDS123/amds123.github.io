---
layout: post
title: "Generic Multiview Visual Tracking"
date: 2019-04-04 13:42:12
categories: arXiv_CV
tags: arXiv_CV Tracking Prediction Relation
author: Minye Wu, Haibin Ling, Ning Bi, Shenghua Gao, Hao Sheng, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progresses in visual tracking have greatly improved the tracking performance. However, challenges such as occlusion and view change remain obstacles in real world deployment. A natural solution to these challenges is to use multiple cameras with multiview inputs, though existing systems are mostly limited to specific targets (e.g. human), static cameras, and/or camera calibration. To break through these limitations, we propose a generic multiview tracking (GMT) framework that allows camera movement, while requiring neither specific object model nor camera calibration. A key innovation in our framework is a cross-camera trajectory prediction network (TPN), which implicitly and dynamically encodes camera geometric relations, and hence addresses missing target issues such as occlusion. Moreover, during tracking, we assemble information across different cameras to dynamically update a novel collaborative correlation filter (CCF), which is shared among cameras to achieve robustness against view change. The two components are integrated into a correlation filter tracking framework, where the features are trained offline using existing single view tracking datasets. For evaluation, we first contribute a new generic multiview tracking dataset (GMTD) with careful annotations, and then run experiments on GMTD and the PETS2009 datasets. On both datasets, the proposed GMT algorithm shows clear advantages over state-of-the-art ones.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02553](http://arxiv.org/abs/1904.02553)

##### PDF
[http://arxiv.org/pdf/1904.02553](http://arxiv.org/pdf/1904.02553)

