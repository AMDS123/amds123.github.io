---
layout: post
title: "Detection and Tracking of General Movable Objects in Large 3D Maps"
date: 2018-01-30 09:31:47
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Nils Bore, Johan Ekekrantz, Patric Jensfelt, John Folkesson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problem of detection and tracking of general objects with long-term dynamics, observed by a mobile robot moving in a large environment. A key problem is that due to the environment scale, it can only observe a subset of the objects at any given time. Since some time passes between observations of objects in different places, the objects might be moved when the robot is not there. We propose a model for this movement in which the objects typically only move locally, but with some small probability they jump longer distances, through what we call global motion. For filtering, we decompose the posterior over local and global movements into two linked processes. The posterior over the global movements and measurement associations is sampled, while we track the local movement analytically using Kalman filters. This novel filter is evaluated on point cloud data gathered autonomously by a mobile robot over an extended period of time. We show that tracking jumping objects is feasible, and that the proposed probabilistic treatment outperforms previous methods when applied to real world data. The key to efficient probabilistic tracking in this scenario is focused sampling of the object posteriors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.08409](https://arxiv.org/abs/1712.08409)

##### PDF
[https://arxiv.org/pdf/1712.08409](https://arxiv.org/pdf/1712.08409)

