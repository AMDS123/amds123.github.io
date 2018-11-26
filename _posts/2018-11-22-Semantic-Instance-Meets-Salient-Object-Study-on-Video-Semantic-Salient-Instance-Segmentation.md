---
layout: post
title: "Semantic Instance Meets Salient Object: Study on Video Semantic Salient Instance Segmentation"
date: 2018-11-22 06:11:28
categories: arXiv_CV
tags: arXiv_CV Salient Semantic_Instance_Segmentation Segmentation Tracking
author: Trung-Nghia Le, Akihiro Sugimoto
mathjax: true
---

* content
{:toc}

##### Abstract
Focusing on only semantic instances that only salient in a scene gains more benefits for robot navigation and self-driving cars than looking at all objects in the whole scene. This paper pushes the envelope on salient regions in a video to decompose them into semantically meaningful components, namely, semantic salient instances. We provide the baseline for the new task of video semantic salient instance segmentation (VSSIS), that is, Semantic Instance - Salient Object (SISO) framework. The SISO framework is simple yet efficient, leveraging advantages of two different segmentation tasks, i.e. semantic instance segmentation and salient object segmentation to eventually fuse them for the final result. In SISO, we introduce a sequential fusion by looking at overlapping pixels between semantic instances and salient regions to have non-overlapping instances one by one. We also introduce a recurrent instance propagation to refine the shapes and semantic meanings of instances, and an identity tracking to maintain both the identity and the semantic meaning of instances over the entire video. Experimental results demonstrated the effectiveness of our SISO baseline, which can handle occlusions in videos. In addition, to tackle the task of VSSIS, we augment the DAVIS-2017 benchmark dataset by assigning semantic ground-truth for salient instance labels, obtaining SEmantic Salient Instance Video (SESIV) dataset. Our SESIV dataset consists of 84 high-quality video sequences with pixel-wisely per-frame ground-truth labels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.01452](http://arxiv.org/abs/1807.01452)

##### PDF
[http://arxiv.org/pdf/1807.01452](http://arxiv.org/pdf/1807.01452)

