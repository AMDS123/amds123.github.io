---
layout: post
title: "Epipolar Geometry based Learning of Multi-view Depth and Ego-Motion from Monocular Sequences"
date: 2018-12-23 09:26:49
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: Vignesh Prasad, Dipanjan Das, Brojeshwar Bhowmick
mathjax: true
---

* content
{:toc}

##### Abstract
Deep approaches to predict monocular depth and ego-motion have grown in recent years due to their ability to produce dense depth from monocular images. The main idea behind them is to optimize the photometric consistency over image sequences by warping one view into another, similar to direct visual odometry methods. One major drawback is that these methods infer depth from a single view, which might not effectively capture the relation between pixels. Moreover, simply minimizing the photometric loss does not ensure proper pixel correspondences, which is a key factor for accurate depth and pose estimations. 
 In contrast, we propose a 2-view depth network to infer the scene depth from consecutive frames, thereby learning inter-pixel relationships. To ensure better correspondences, thereby better geometric understanding, we propose incorporating epipolar constraints to make the learning more geometrically sound. We use the Essential matrix obtained using Nist'er's Five Point Algorithm, to enforce meaningful geometric constraints, rather than using it as training labels. This allows us to use lesser no. of trainable parameters compared to state-of-the-art methods. The proposed method results in better depth images and pose estimates, which capture the scene structure and motion in a better way. Such a geometrically constrained learning performs successfully even in cases where simply minimizing the photometric error would fail.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11922](http://arxiv.org/abs/1812.11922)

##### PDF
[http://arxiv.org/pdf/1812.11922](http://arxiv.org/pdf/1812.11922)

