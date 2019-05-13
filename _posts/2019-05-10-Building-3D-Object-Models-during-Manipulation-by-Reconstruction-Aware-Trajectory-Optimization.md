---
layout: post
title: "Building 3D Object Models during Manipulation by Reconstruction-Aware Trajectory Optimization"
date: 2019-05-10 01:33:29
categories: arXiv_AI
tags: arXiv_AI Face Optimization
author: Kanrun Huang, Tucker Hermans
mathjax: true
---

* content
{:toc}

##### Abstract
Object shape provides important information for robotic manipulation; for instance, selecting an effective grasp depends on both the global and local shape of the object of interest, while reaching into clutter requires accurate surface geometry to avoid unintended contact with the environment. Model-based 3D object manipulation is a widely studied problem; however, obtaining the accurate 3D object models for multiple objects often requires tedious work. In this letter, we exploit Gaussian process implicit surfaces (GPIS) extracted from RGB-D sensor data to grasp an unknown object. We propose a reconstruction-aware trajectory optimization that makes use of the extracted GPIS model plan a motion to improve the ability to estimate the object's 3D geometry, while performing a pick-and-place action. We present a probabilistic approach for a robot to autonomously learn and track the object, while achieve the manipulation task. 
 We use a sampling-based trajectory generation method to explore the unseen parts of the object using the estimated conditional entropy of the GPIS model. We validate our method with physical robot experiments across eleven different objects of varying shape from the YCB object dataset. Our experiments show that our reconstruction-aware trajectory optimization provides higher-quality 3D object reconstruction when compared with directly solving the manipulation task or using a heuristic to view unseen portions of the object.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03907](http://arxiv.org/abs/1905.03907)

##### PDF
[http://arxiv.org/pdf/1905.03907](http://arxiv.org/pdf/1905.03907)

