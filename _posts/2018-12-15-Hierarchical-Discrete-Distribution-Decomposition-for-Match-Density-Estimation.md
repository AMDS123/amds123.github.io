---
layout: post
title: "Hierarchical Discrete Distribution Decomposition for Match Density Estimation"
date: 2018-12-15 09:37:58
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Zhichao Yin, Trevor Darrell, Fisher Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep learning methods for pixel correspondence output a point estimate of the motion field, but do not represent the full match distribution. Explicit representation of a match distribution is desirable for many applications as it allows direct representation of the correspondence probability. The main difficulty of estimating a full probability distribution with a deep network is the high computational cost of inferring the entire distribution. In this paper, we propose Hierarchical Discrete Distribution Decomposition, dubbed HD$^3$, to learn probabilistic point and region matching. Not only can it model match uncertainty, but also region propagation. To achieve this, we estimate the hierarchical distribution of pixel correspondences at different image scales without multi-hypotheses ensembling. Despite its simplicity, our method can achieve competitive results for both optical flow and stereo matching on established benchmarks, while the estimated uncertainty is a good indicator of errors. Furthermore, the point match distribution within a region can be grouped together to propagate the whole region even if the area changes across images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06264](http://arxiv.org/abs/1812.06264)

##### PDF
[http://arxiv.org/pdf/1812.06264](http://arxiv.org/pdf/1812.06264)

