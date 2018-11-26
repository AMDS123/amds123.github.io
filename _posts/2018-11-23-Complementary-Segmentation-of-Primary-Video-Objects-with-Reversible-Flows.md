---
layout: post
title: "Complementary Segmentation of Primary Video Objects with Reversible Flows"
date: 2018-11-23 15:29:38
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation
author: Jia Li, Junjie Wu, Anlin Zheng, Yafei Song, Yu Zhang, Xiaowu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting primary objects in a video is an important yet challenging problem in computer vision, as it exhibits various levels of foreground/background ambiguities. To reduce such ambiguities, we propose a novel formulation via exploiting foreground and background context as well as their complementary constraint. Under this formulation, a unified objective function is further defined to encode each cue. For implementation, we design a Complementary Segmentation Network (CSNet) with two separate branches, which can simultaneously encode the foreground and background information along with joint spatial constraints. The CSNet is trained on massive images with manually annotated salient objects in an end-to-end manner. By applying CSNet on each video frame, the spatial foreground and background maps can be initialized. To enforce temporal consistency effectively and efficiently, we divide each frame into superpixels and construct neighborhood reversible flow that reflects the most reliable temporal correspondences between superpixels in far-away frames. With such flow, the initialized foregroundness and backgroundness can be propagated along the temporal dimension so that primary video objects gradually pop-out and distractors are well suppressed. Extensive experimental results on three video datasets show that the proposed approach achieves impressive performance in comparisons with 18 state-of-the-art models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09521](http://arxiv.org/abs/1811.09521)

##### PDF
[http://arxiv.org/pdf/1811.09521](http://arxiv.org/pdf/1811.09521)

