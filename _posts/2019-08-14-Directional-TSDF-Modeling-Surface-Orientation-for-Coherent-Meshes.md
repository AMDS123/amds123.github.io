---
layout: post
title: "Directional TSDF: Modeling Surface Orientation for Coherent Meshes"
date: 2019-08-14 14:27:52
categories: arXiv_CV
tags: arXiv_CV Face
author: Malte Splietker, Sven Behnke
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time 3D reconstruction from RGB-D sensor data plays an important role in many robotic applications, such as object modeling and mapping. The popular method of fusing depth information into a truncated signed distance function (TSDF) and applying the marching cubes algorithm for mesh extraction has severe issues with thin structures: not only does it lead to loss of accuracy, but it can generate completely wrong surfaces. To address this, we propose the directional TSDF - a novel representation that stores opposite surfaces separate from each other. The marching cubes algorithm is modified accordingly to retrieve a coherent mesh representation. We further increase the accuracy by using surface gradient-based ray casting for fusing new measurements. We show that our method outperforms state-of-the-art TSDF reconstruction algorithms in mesh accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05146](http://arxiv.org/abs/1908.05146)

##### PDF
[http://arxiv.org/pdf/1908.05146](http://arxiv.org/pdf/1908.05146)

