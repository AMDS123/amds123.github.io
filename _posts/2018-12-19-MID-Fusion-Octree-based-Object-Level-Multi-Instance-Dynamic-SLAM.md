---
layout: post
title: "MID-Fusion: Octree-based Object-Level Multi-Instance Dynamic SLAM"
date: 2018-12-19 14:43:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Quantitative SLAM
author: Binbin Xu, Wenbin Li, Dimos Tzoumanikas, Michael Bloesch, Andrew Davison, Stefan Leutenegger
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new multi-instance dynamic RGB-D SLAM system using an object-level octree-based volumetric representation. It can provide robust camera tracking in dynamic environments and at the same time, continuously estimate geometric, semantic, and motion properties for arbitrary objects in the scene. For each incoming frame, we perform instance segmentation to detect objects and refine mask boundaries using geometric and motion information. Meanwhile, we estimate the pose of each existing moving object using an object-oriented tracking method and robustly track the camera pose against the static scene. Based on the estimated camera pose and object poses, we associate segmented masks with existing models and incrementally fuse corresponding colour, depth, semantic, and foreground object probabilities into each object model. In contrast to existing approaches, our system is the first system to generate an object-level dynamic volumetric map from a single RGB-D camera, which can be used directly for robotic tasks. Our method can run at 2-3 Hz on a CPU, excluding the instance segmentation part. We demonstrate its effectiveness by quantitatively and qualitatively testing it on both synthetic and real-world sequences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07976](http://arxiv.org/abs/1812.07976)

##### PDF
[http://arxiv.org/pdf/1812.07976](http://arxiv.org/pdf/1812.07976)

