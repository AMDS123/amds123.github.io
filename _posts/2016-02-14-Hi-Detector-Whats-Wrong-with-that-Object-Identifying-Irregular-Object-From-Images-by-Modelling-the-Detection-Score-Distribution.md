---
layout: post
title: "Hi Detector, What's Wrong with that Object? Identifying Irregular Object From Images by Modelling the Detection Score Distribution"
date: 2016-02-14 06:39:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Peng Wang, Lingqiao Liu, Chunhua Shen, Anton van den Hengel, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we study the challenging problem of identifying the irregular status of objects from images in an "open world" setting, that is, distinguishing the irregular status of an object category from its regular status as well as objects from other categories in the absence of "irregular object" training data. To address this problem, we propose a novel approach by inspecting the distribution of the detection scores at multiple image regions based on the detector trained from the "regular object" and "other objects". The key observation motivating our approach is that for "regular object" images as well as "other objects" images, the region-level scores follow their own essential patterns in terms of both the score values and the spatial distributions while the detection scores obtained from an "irregular object" image tend to break these patterns. To model this distribution, we propose to use Gaussian Processes (GP) to construct two separate generative models for the case of the "regular object" and the "other objects". More specifically, we design a new covariance function to simultaneously model the detection score at a single region and the score dependencies at multiple regions. We finally demonstrate the superior performance of our method on a large dataset newly proposed in this paper.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1602.04422](https://arxiv.org/abs/1602.04422)

##### PDF
[https://arxiv.org/pdf/1602.04422](https://arxiv.org/pdf/1602.04422)

