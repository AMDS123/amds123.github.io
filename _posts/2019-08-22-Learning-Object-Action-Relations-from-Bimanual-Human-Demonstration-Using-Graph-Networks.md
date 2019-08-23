---
layout: post
title: "Learning Object-Action Relations from Bimanual Human Demonstration Using Graph Networks"
date: 2019-08-22 14:02:18
categories: arXiv_RO
tags: arXiv_RO Object_Detection Segmentation Pose_Estimation Action_Recognition Classification Prediction Detection Relation Recognition
author: Christian R. G. Dreher, Mirko Wächter, Tamim Asfour
mathjax: true
---

* content
{:toc}

##### Abstract
Recognising human actions is a vital task for a humanoid robot, especially in domains like programming by demonstration. Previous approaches on action recognition primarily focused on the overall prevalent action being executed, but we argue that bimanual human motion cannot always be described sufficiently with a single label. We therefore present a novel approach for action classification and segmentation by learning object-action relations, while considering the actions executed by each hand individually. Interpreting the scene as a graph of symbolic spatial relations between the hands and objects enables us to train a neural network architecture specifically designed to operate on variable-sized graphs. In order to produce scene graphs, we present a feature extraction pipeline involving human pose estimation and object detection for the calculation of the spatial relations from RGB-D videos. We evaluated the proposed classifier on a new RGB-D video dataset showing daily action sequences focusing on bimanual manipulation actions. It consists of 6 subjects performing 9 tasks with 10 repetitions each, which leads to 540 video recordings with 2 hours and 18 minutes total playtime and per-hand ground truth action labels for each frame. We show that our classifier is able to reliably identify (macro F1-score of 0.86) the true executed action of each hand within its top 3 predictions on a frame-by-frame basis without prior temporal action segmentation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08391](https://arxiv.org/abs/1908.08391)

##### PDF
[https://arxiv.org/pdf/1908.08391](https://arxiv.org/pdf/1908.08391)

