---
layout: post
title: "Scene Motion Decomposition for Learnable Visual Odometry"
date: 2019-07-16 19:38:32
categories: arXiv_CV
tags: arXiv_CV
author: Igor Slinko, Anna Vorontsova, Filipp Konokhov, Olga Barinova, Anton Konushin
mathjax: true
---

* content
{:toc}

##### Abstract
Optical Flow (OF) and depth are commonly used for visual odometry since they provide sufficient information about camera ego-motion in a rigid scene. We reformulate the problem of ego-motion estimation as a problem of motion estimation of a 3D-scene with respect to a static camera. The entire scene motion can be represented as a combination of motions of its visible points. Using OF and depth we estimate a motion of each point in terms of 6DoF and represent results in the form of motion maps, each one addressing single degree of freedom. In this work we provide motion maps as inputs to a deep neural network that predicts 6DoF of scene motion. Through our evaluation on outdoor and indoor datasets we show that utilizing motion maps leads to accuracy improvement in comparison with naive stacking of depth and OF. Another contribution of our work is a novel network architecture that efficiently exploits motion maps and outperforms learnable RGB/RGB-D baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07227](http://arxiv.org/abs/1907.07227)

##### PDF
[http://arxiv.org/pdf/1907.07227](http://arxiv.org/pdf/1907.07227)

