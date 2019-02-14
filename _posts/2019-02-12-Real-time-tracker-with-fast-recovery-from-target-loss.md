---
layout: post
title: "Real-time tracker with fast recovery from target loss"
date: 2019-02-12 11:28:15
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Alessandro Bay, Panagiotis Sidiropoulos, Eduard Vazquez, Michele Sasdelli
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a variation of a state-of-the-art real-time tracker (CFNet), which adds to the original algorithm robustness to target loss without a significant computational overhead. The new method is based on the assumption that the feature map can be used to estimate the tracking confidence more accurately. When the confidence is low, we avoid updating the object's position through the feature map; instead, the tracker passes to a single-frame failure mode, during which the patch's low-level visual content is used to swiftly update the object's position, before recovering from the target loss in the next frame. The experimental evidence provided by evaluating the method on several tracking datasets validates both the theoretical assumption that the feature map is associated to tracking confidence, and that the proposed implementation can achieve target recovery in multiple scenarios, without compromising the real-time performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04570](http://arxiv.org/abs/1902.04570)

##### PDF
[http://arxiv.org/pdf/1902.04570](http://arxiv.org/pdf/1902.04570)

