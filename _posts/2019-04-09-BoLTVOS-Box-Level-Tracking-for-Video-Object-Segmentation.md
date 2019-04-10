---
layout: post
title: "BoLTVOS: Box-Level Tracking for Video Object Segmentation"
date: 2019-04-09 09:16:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking Detection
author: Paul Voigtlaender, Jonathon Luiten, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
We approach video object segmentation (VOS) by splitting the task into two sub-tasks: bounding box level tracking, followed by bounding box segmentation. Following this paradigm, we present BoLTVOS (Box-Level Tracking for VOS), which consists of an R-CNN detector conditioned on the first-frame bounding box to detect the object of interest, a temporal consistency rescoring algorithm, and a Box2Seg network that converts bounding boxes to segmentation masks. BoLTVOS performs VOS using only the firstframe bounding box without the mask. We evaluate our approach on DAVIS 2017 and YouTube-VOS, and show that it outperforms all methods that do not perform first-frame fine-tuning. We further present BoLTVOS-ft, which learns to segment the object in question using the first-frame mask while it is being tracked, without increasing the runtime. BoLTVOS-ft outperforms PReMVOS, the previously best performing VOS method on DAVIS 2016 and YouTube-VOS, while running up to 45 times faster. Our bounding box tracker also outperforms all previous short-term and longterm trackers on the bounding box level tracking datasets OTB 2015 and LTB35.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04552](http://arxiv.org/abs/1904.04552)

##### PDF
[http://arxiv.org/pdf/1904.04552](http://arxiv.org/pdf/1904.04552)

