---
layout: post
title: "Real-time Multiple People Hand Localization in 4D Point Clouds"
date: 2019-03-05 06:46:35
categories: arXiv_CV
tags: arXiv_CV
author: Hao Jiang, Quanzeng You
mathjax: true
---

* content
{:toc}

##### Abstract
We propose novel real-time algorithm to localize hands and find their associations with multiple people in the cluttered 4D volumetric data (dynamic 3D volumes). Different from the traditional multiple view approaches, which find key points in 2D and then triangulate to recover the 3D locations, our method directly processes the dynamic 3D data that involve both clutter and crowd. The volumetric representation is more desirable than the partial observations from different view points and enables more robust and accurate results. However, due to the large amount of data in the volumetric representation brute force 3D schemes are slow. In this paper, we propose novel real-time methods to tackle the problem to achieve both higher accuracy and faster speed than previous approaches. Our method detects the 3D bounding box of each subject and localizes the hands of each person. We develop new 2D features for fast candidate proposals and optimize the trajectory linking using a new max-covering bipartite matching formulation, which is critical for robust performance. We propose a novel decomposition method to reduce the key point localization in each person 3D volume to a sequence of efficient 2D problems. Our experiments show that the proposed method is faster than different competing methods and it gives almost half the localization error.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01695](https://arxiv.org/abs/1903.01695)

##### PDF
[https://arxiv.org/pdf/1903.01695](https://arxiv.org/pdf/1903.01695)

