---
layout: post
title: "Design Pseudo Ground Truth with Motion Cue for Unsupervised Video Object Segmentation"
date: 2018-12-13 00:13:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking Semantic_Segmentation
author: Ye Wang, Jongmoo Choi, Yueru Chen, Qin Huang, Siyang Li, Ming-Sui Lee, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
One major technique debt in video object segmentation is to label the object masks for training instances. As a result, we propose to prepare inexpensive, yet high quality pseudo ground truth corrected with motion cue for video object segmentation training. Our method conducts semantic segmentation using instance segmentation networks and, then, selects the segmented object of interest as the pseudo ground truth based on the motion information. Afterwards, the pseudo ground truth is exploited to finetune the pretrained objectness network to facilitate object segmentation in the remaining frames of the video. We show that the pseudo ground truth could effectively improve the segmentation performance. This straightforward unsupervised video object segmentation method is more efficient than existing methods. Experimental results on DAVIS and FBMS show that the proposed method outperforms state-of-the-art unsupervised segmentation methods on various benchmark datasets. And the category-agnostic pseudo ground truth has great potential to extend to multiple arbitrary object tracking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05206](http://arxiv.org/abs/1812.05206)

##### PDF
[http://arxiv.org/pdf/1812.05206](http://arxiv.org/pdf/1812.05206)

