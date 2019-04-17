---
layout: post
title: "Hierarchical Discrete Distribution Decomposition for Match Density Estimation"
date: 2019-04-16 05:11:00
categories: arXiv_CV
tags: arXiv_CV
author: Zhichao Yin, Trevor Darrell, Fisher Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Explicit representations of the global match distributions of pixel-wise correspondences between pairs of images are desirable for uncertainty estimation and downstream applications. However, the computation of the match density for each pixel may be prohibitively expensive due to the large number of candidates. In this paper, we propose Hierarchical Discrete Distribution Decomposition (HD^3), a framework suitable for learning probabilistic pixel correspondences in both optical flow and stereo matching. We decompose the full match density into multiple scales hierarchically, and estimate the local matching distributions at each scale conditioned on the matching and warping at coarser scales. The local distributions can then be composed together to form the global match density. Despite its simplicity, our probabilistic method achieves state-of-the-art results for both optical flow and stereo matching on established benchmarks. We also find the estimated uncertainty is a good indication of the reliability of the predicted correspondences.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06264](http://arxiv.org/abs/1812.06264)

##### PDF
[http://arxiv.org/pdf/1812.06264](http://arxiv.org/pdf/1812.06264)

