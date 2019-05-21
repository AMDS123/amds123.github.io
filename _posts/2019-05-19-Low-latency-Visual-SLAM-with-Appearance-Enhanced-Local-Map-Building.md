---
layout: post
title: "Low-latency Visual SLAM with Appearance-Enhanced Local Map Building"
date: 2019-05-19 19:34:03
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking SLAM
author: Yipu Zhao, Wenkai Ye, Patricio A. Vela
mathjax: true
---

* content
{:toc}

##### Abstract
A local map module is often implemented in modern VO/VSLAM systems to improve data association and pose estimation. Conventionally, the local map contents are determined by co-visibility. While co-visibility is cheap to establish, it utilizes the relatively-weak temporal prior (i.e. seen before, likely to be seen now), therefore admitting more features into the local map than necessary. This paper describes an enhancement to co-visibility local map building by incorporating a strong appearance prior, which leads to a more compact local map and latency reduction in downstream data association. The appearance prior collected from the current image influences the local map contents: only the map features visually similar to the current measurements are potentially useful for data association. To that end, mapped features are indexed and queried with Multi-index Hashing (MIH). An online hash table selection algorithm is developed to further reduce the query overhead of MIH and the local map size. The proposed appearance-based local map building method is integrated into a state-of-the-art VO/VSLAM system. When evaluated on two public benchmarks, the size of the local map, as well as the latency of real-time pose tracking in VO/VSLAM are significantly reduced. Meanwhile, the VO/VSLAM mean performance is preserved or improves.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07797](http://arxiv.org/abs/1905.07797)

##### PDF
[http://arxiv.org/pdf/1905.07797](http://arxiv.org/pdf/1905.07797)

