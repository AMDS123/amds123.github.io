---
layout: post
title: "Lightweight Markerless Monocular Face Capture with 3D Spatial Priors"
date: 2019-01-16 15:51:25
categories: arXiv_CV
tags: arXiv_CV Face Tracking Quantitative
author: Shridhar Ravikumar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple lightweight markerless facial performance capture framework using just a monocular video input that combines Active Appearance Models for feature tracking and prior constraints on 3D shapes into an integrated objective function. 2D monocular inputs inherently lack information along the depth axis and can lead to physically implausible solutions. In order to address this loss of information, we enforce a constraint on our objective function within a probabilistic framework that uses preexisting animations obtained from accurate 3D tracking systems, thus achieving more plausible results. Our system fits a Blendshape model to tracked 2D features while also handling noise in estimation of features and camera parameters. We learn separate constraints for the upper and lower regions of the face thus maintaining flexibility. We show that using this approach, we can obtain significant improvement in tracking especially along the depth dimension. Our method uses easily obtainable prior animation data. We show that our method can generate convincing animations using only a monocular video input. We quantitatively evaluate our results comparing it with an approach using a monocular input without our spatial constraints and show that our results are closer to the ground-truth geometry. Finally, we also evaluate the effect that the choice of the Blendshape set has on the results of the solver by solving for a different set of Blendshapes and quantitatively comparing it with our previous results and to the ground truth. We show that while the choice of Blendshapes does make a difference, the use of our spatial constraints generates results that are closer to the ground truth.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05355](http://arxiv.org/abs/1901.05355)

##### PDF
[http://arxiv.org/pdf/1901.05355](http://arxiv.org/pdf/1901.05355)

