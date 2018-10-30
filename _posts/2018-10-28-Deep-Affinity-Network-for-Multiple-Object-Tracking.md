---
layout: post
title: "Deep Affinity Network for Multiple Object Tracking"
date: 2018-10-28 09:07:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Deep_Learning Detection
author: ShiJie Sun, Naveed Akhtar, HuanSheng Song, Ajmal Mian, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple Object Tracking (MOT) plays an important role in solving many fundamental problems in video analysis in computer vision. Most MOT methods employ two steps: Object Detection and Data Association. The first step detects objects of interest in every frame of a video, and the second establishes correspondence between the detected objects in different frames to obtain their tracks. Object detection has made tremendous progress in the last few years due to deep learning. However, data association for tracking still relies on hand crafted constraints such as appearance, motion, spatial proximity, grouping etc. to compute affinities between the objects in different frames. In this paper, we harness the power of deep learning for data association in tracking by jointly modelling object appearances and their affinities between different frames in an end-to-end fashion. The proposed Deep Affinity Network (DAN) learns compact; yet comprehensive features of pre-detected objects at several levels of abstraction, and performs exhaustive pairing permutations of those features in any two frames to infer object affinities. DAN also accounts for multiple objects appearing and disappearing between video frames. We exploit the resulting efficient affinity computations to associate objects in the current frame deep into the previous frames for reliable on-line tracking. Our technique is evaluated on popular multiple object tracking challenges MOT15, MOT17 and UA-DETRAC. Comprehensive benchmarking under twelve evaluation metrics demonstrates that our approach is among the best performing techniques on the leader board for these challenges. The open source implementation of our work is available at https://github.com/shijieS/SST.git.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11780](http://arxiv.org/abs/1810.11780)

##### PDF
[http://arxiv.org/pdf/1810.11780](http://arxiv.org/pdf/1810.11780)

