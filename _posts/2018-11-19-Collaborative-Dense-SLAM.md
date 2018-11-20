---
layout: post
title: "Collaborative Dense SLAM"
date: 2018-11-19 11:54:40
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation Quantitative SLAM Recognition
author: Louis Gallagher, John B. McDonald
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a new system for live collaborative dense surface reconstruction. Cooperative robotics, multi participant augmented reality and human-robot interaction are all examples of situations where collaborative mapping can be leveraged for greater agent autonomy. Our system builds on ElasticFusion to allow a number of cameras starting with unknown initial relative positions to maintain local maps utilising the original algorithm. Carrying out visual place recognition across these local maps the system can identify when two maps overlap in space, providing an inter-map constraint from which the system can derive the relative poses of the two maps. Using these resulting pose constraints, our system performs map merging, allowing multiple cameras to fuse their measurements into a single shared reconstruction. The advantage of this approach is that it avoids replication of structures subsequent to loop closures, where multiple cameras traverse the same regions of the environment. Furthermore, it allows cameras to directly exploit and update regions of the environment previously mapped by other cameras within the system. We provide both quantitative and qualitative analyses using the synthetic ICL-NUIM dataset and the real-world Freiburg dataset including the impact of multi-camera mapping on surface reconstruction accuracy, camera pose estimation accuracy and overall processing time. We also include qualitative results in the form of sample reconstructions of room sized environments with up to 3 cameras undergoing intersecting and loopy trajectories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07632](http://arxiv.org/abs/1811.07632)

##### PDF
[http://arxiv.org/pdf/1811.07632](http://arxiv.org/pdf/1811.07632)

