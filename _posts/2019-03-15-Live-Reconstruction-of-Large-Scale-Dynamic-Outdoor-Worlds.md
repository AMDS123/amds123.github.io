---
layout: post
title: "Live Reconstruction of Large-Scale Dynamic Outdoor Worlds"
date: 2019-03-15 15:50:59
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Quantitative
author: Ondrej Miksik, Vibhav Vineet
mathjax: true
---

* content
{:toc}

##### Abstract
Standard 3D reconstruction pipelines assume stationary world, therefore suffer from ``ghost artifacts'' whenever dynamic objects are present in the scene. Recent approaches has started tackling this issue, however, they typically either only discard dynamic information, represent it using bounding boxes or per-frame depth or rely on approaches that are inherently slow and not suitable to online settings. 
 We propose an end-to-end system for live reconstruction of large-scale outdoor dynamic environments. We leverage recent advances in computationally efficient data-driven approaches for 6 DoF object pose estimation to segment the scene into objects and stationary ``background''. This allows us to represent the scene using a time-dependent (dynamic) map, in which each object is explicitly represented as a separate instance and reconstructed in its own volume. For each time step, our dynamic map maintains a relative pose of each volume with respect to the stationary background. Our system operates in incremental manner which is essential for on-line reconstruction, handles large-scale environments with objects at large distances and runs in (near) real-time. We demonstrate the efficacy of our approach on the KITTI dataset, and provide qualitative and quantitative results showing high-quality dense 3D reconstructions of a number of dynamic scenes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06708](http://arxiv.org/abs/1903.06708)

##### PDF
[http://arxiv.org/pdf/1903.06708](http://arxiv.org/pdf/1903.06708)

