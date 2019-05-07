---
layout: post
title: "Bayesian Scale Estimation for Monocular SLAM Based on Generic Object Detection for Correcting Scale Drift"
date: 2017-11-07 23:28:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Quantitative Detection SLAM
author: Edgar Sucar, Jean-Bernard Hayet
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a new, online algorithm for estimating the local scale correction to apply to the output of a monocular SLAM system and obtain an as faithful as possible metric reconstruction of the 3D map and of the camera trajectory. Within a Bayesian framework, it integrates observations from a deep-learning based generic object detector and a prior on the evolution of the scale drift. For each observation class, a predefined prior on the heights of the class objects is used. This allows to define the observations likelihood. Due to the scale drift inherent to monocular SLAM systems, we integrate a rough model on the dynamics of scale drift. Quantitative evaluations of the system are presented on the KITTI dataset, and compared with different approaches. The results show a superior performance of our proposal in terms of relative translational error when compared to other monocular systems.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.02768](https://arxiv.org/abs/1711.02768)

##### PDF
[https://arxiv.org/pdf/1711.02768](https://arxiv.org/pdf/1711.02768)

