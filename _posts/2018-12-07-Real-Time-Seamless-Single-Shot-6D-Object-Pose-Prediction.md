---
layout: post
title: "Real-Time Seamless Single Shot 6D Object Pose Prediction"
date: 2018-12-07 09:38:58
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Bugra Tekin, Sudipta N. Sinha, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a single-shot approach for simultaneously detecting an object in an RGB image and predicting its 6D pose without requiring multiple stages or having to examine multiple hypotheses. Unlike a recently proposed single-shot technique for this task (Kehl et al., ICCV'17) that only predicts an approximate 6D pose that must then be refined, ours is accurate enough not to require additional post-processing. As a result, it is much faster - 50 fps on a Titan X (Pascal) GPU - and more suitable for real-time processing. The key component of our method is a new CNN architecture inspired by the YOLO network design that directly predicts the 2D image locations of the projected vertices of the object's 3D bounding box. The object's 6D pose is then estimated using a PnP algorithm. 
 For single object and multiple object pose estimation on the LINEMOD and OCCLUSION datasets, our approach substantially outperforms other recent CNN-based approaches when they are all used without post-processing. During post-processing, a pose refinement step can be used to boost the accuracy of the existing methods, but at 10 fps or less, they are much slower than our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.08848](http://arxiv.org/abs/1711.08848)

##### PDF
[http://arxiv.org/pdf/1711.08848](http://arxiv.org/pdf/1711.08848)

