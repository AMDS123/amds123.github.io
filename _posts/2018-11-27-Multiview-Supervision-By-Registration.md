---
layout: post
title: "Multiview Supervision By Registration"
date: 2018-11-27 20:46:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection Relation
author: Yilun Zhang, Hyun Soo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a semi-supervised learning framework to train a keypoint pose detector using multiview image streams given the limited number of labeled data (typically &lt;4%). We leverage the complementary relationship between multiview geometry and visual tracking to provide three types of supervisionary signals for the unlabeled data: (1) pose detection in one view can be used to supervise that of the other view as they must satisfy the epipolar constraint; (2) pose detection must be temporally coherent in accordance with its optical flow; (3) the occluded keypoint from one view must be consistently invisible from the near views. We formulate the theory of multiview supervision by registration and design a new end-to-end neural network that integrates these supervisionary signals in a differentiable fashion to incorporate the large unlabeled data in pose detector training. The key innovation of the network is the ability to reason about the visibility/occlusion, which is indicative of the degenerate case of detection and tracking. Our resulting pose detector shows considerable outperformance comparing the state-of-the-art pose detectors in terms of accuracy (keypoint detection) and precision (3D reconstruction). We validate our approach with challenging realworld data including the pose detection of non-human species such as monkeys and dogs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11251](http://arxiv.org/abs/1811.11251)

##### PDF
[http://arxiv.org/pdf/1811.11251](http://arxiv.org/pdf/1811.11251)

