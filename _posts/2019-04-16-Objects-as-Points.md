---
layout: post
title: "Objects as Points"
date: 2019-04-16 17:54:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xingyi Zhou, Dequan Wang, Philipp Kr&#xe4;henb&#xfc;hl
mathjax: true
---

* content
{:toc}

##### Abstract
Detection identifies objects as axis-aligned boxes in an image. Most successful object detectors enumerate a nearly exhaustive list of potential object locations and classify each. This is wasteful, inefficient, and requires additional post-processing. In this paper, we take a different approach. We model an object as a single point --- the center point of its bounding box. Our detector uses keypoint estimation to find center points and regresses to all other object properties, such as size, 3D location, orientation, and even pose. Our center point based approach, CenterNet, is end-to-end differentiable, simpler, faster, and more accurate than corresponding bounding box based detectors. CenterNet achieves the best speed-accuracy trade-off on the MS COCO dataset, with 28.1% AP at 142 FPS, 37.4% AP at 52 FPS, and 45.1% AP with multi-scale testing at 1.4 FPS. We use the same approach to estimate 3D bounding box in the KITTI benchmark and human pose on the COCO keypoint dataset. Our method performs competitively with sophisticated multi-stage methods and runs in real-time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07850](http://arxiv.org/abs/1904.07850)

##### PDF
[http://arxiv.org/pdf/1904.07850](http://arxiv.org/pdf/1904.07850)

