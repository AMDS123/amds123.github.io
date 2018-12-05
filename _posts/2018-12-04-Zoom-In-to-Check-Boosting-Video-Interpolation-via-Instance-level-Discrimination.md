---
layout: post
title: "Zoom-In-to-Check: Boosting Video Interpolation via Instance-level Discrimination"
date: 2018-12-04 04:17:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection CNN Detection
author: Liangzhe Yuan, Yibo Chen, Hantian Liu, Tao Kong, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a light-weight video frame interpolation algorithm. Our key innovation is an instance-level supervision that allows information to be learned from the high-resolution version of similar objects. Our experiment shows that the proposed method can generate state-of-art results across different datasets, with fractional computation resources (time and memory) with competing methods. Given two image frames, a cascade network creates an intermediate frame with 1) a flow-warping module that computes large bi-directional optical flow and creates an interpolated image via flow-based warping, followed by 2) an image synthesis module to make fine-scale corrections. In the learning stage, object detection proposals are generated on the interpolated image. Lower resolution objects are zoomed into, and the learning algorithms using an adversarial loss trained on high-resolution objects to guide the system towards the instance-level refinement corrects details of object shape and boundaries. As all our proposed network modules are fully convolutional, our proposed system can be trained end-to-end.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01210](http://arxiv.org/abs/1812.01210)

##### PDF
[http://arxiv.org/pdf/1812.01210](http://arxiv.org/pdf/1812.01210)

