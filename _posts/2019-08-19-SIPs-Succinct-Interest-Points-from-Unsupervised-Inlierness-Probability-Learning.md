---
layout: post
title: "SIPs: Succinct Interest Points from Unsupervised Inlierness Probability Learning"
date: 2019-08-19 13:13:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Titus Cieslewski, Konstantinos G. Derpanis, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
A wide range of computer vision algorithms rely on identifying sparse interest points in images and establishing correspondences between them. However, only a subset of the initially identified interest points results in true correspondences (inliers). In this paper, we seek a detector that finds the minimum number of points that are likely to result in an application-dependent "sufficient" number of inliers k. To quantify this goal, we introduce the "k-succinctness" metric. Extracting a minimum number of interest points is attractive for many applications, because it can reduce computational load, memory, and data transmission. Alongside succinctness, we introduce an unsupervised training methodology for interest point detectors that is based on predicting the probability of a given pixel being an inlier. In comparison to previous learned detectors, our method requires the least amount of data pre-processing. Our detector and other state-of-the-art detectors are extensively evaluated with respect to succinctness on popular public datasets covering both indoor and outdoor scenes, and both wide and narrow baselines. In certain cases, our detector is able to obtain an equivalent amount of inliers with as little as 60% of the amount of points of other detectors. The code and trained networks are provided at https://github.com/uzh-rpg/sips2_open .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.01358](http://arxiv.org/abs/1805.01358)

##### PDF
[http://arxiv.org/pdf/1805.01358](http://arxiv.org/pdf/1805.01358)

