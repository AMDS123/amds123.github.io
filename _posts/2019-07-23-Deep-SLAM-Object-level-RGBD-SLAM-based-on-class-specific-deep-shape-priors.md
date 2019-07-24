---
layout: post
title: "Deep-SLAM++: Object-level RGBD SLAM based on class-specific deep shape priors"
date: 2019-07-23 04:24:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection SLAM
author: Lan Hu, Wanting Xu, Kun Huang, Laurent Kneip
mathjax: true
---

* content
{:toc}

##### Abstract
In an effort to increase the capabilities of SLAM systems and produce object-level representations, the community increasingly investigates the imposition of higher-level priors into the estimation process. One such example is given by employing object detectors to load and register full CAD models. Our work extends this idea to environments with unknown objects and imposes object priors by employing modern class-specific neural networks to generate complete model geometry proposals. The difficulty of using such predictions in a real SLAM scenario is that the prediction performance depends on the view-point and measurement quality, with even small changes of the input data sometimes leading to a large variability in the network output. We propose a discrete selection strategy that finds the best among multiple proposals from different registered views by re-enforcing the agreement with the online depth measurements. The result is an effective object-level RGBD SLAM system that produces compact, high-fidelity, and dense 3D maps with semantic annotations. It outperforms traditional fusion strategies in terms of map completeness and resilience against degrading measurement quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09691](http://arxiv.org/abs/1907.09691)

##### PDF
[http://arxiv.org/pdf/1907.09691](http://arxiv.org/pdf/1907.09691)

