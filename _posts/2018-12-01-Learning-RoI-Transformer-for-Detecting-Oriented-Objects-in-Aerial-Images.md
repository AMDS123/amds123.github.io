---
layout: post
title: "Learning RoI Transformer for Detecting Oriented Objects in Aerial Images"
date: 2018-12-01 06:05:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Jian Ding, Nan Xue, Yang Long, Gui-Song Xia, Qikai Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in aerial images is an active yet challenging task in computer vision because of the birdview perspective, the highly complex backgrounds, and the variant appearances of objects. Especially when detecting densely packed objects in aerial images, methods relying on horizontal proposals for common object detection often introduce mismatches between the Region of Interests (RoIs) and objects. This leads to the common misalignment between the final object classification confidence and localization accuracy. Although rotated anchors have been used to tackle this problem, the design of them always multiplies the number of anchors and dramatically increases the computational complexity. In this paper, we propose a RoI Transformer to address these problems. More precisely, to improve the quality of region proposals, we first designed a Rotated RoI (RRoI) learner to transform a Horizontal Region of Interest (HRoI) into a Rotated Region of Interest (RRoI). Based on the RRoIs, we then proposed a Rotated Position Sensitive RoI Align (RPS-RoI-Align) module to extract rotation-invariant features from them for boosting subsequent classification and regression. Our RoI Transformer is with light weight and can be easily embedded into detectors for oriented object detection. A simple implementation of the RoI Transformer has achieved state-of-the-art performances on two common and challenging aerial datasets, i.e., DOTA and HRSC2016, with a neglectable reduction to detection speed. Our RoI Transformer exceeds the deformable Position Sensitive RoI pooling when oriented bounding-box annotations are available. Extensive experiments have also validated the flexibility and effectiveness of our RoI Transformer. The results demonstrate that it can be easily integrated with other detector architectures and significantly improve the performances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00155](http://arxiv.org/abs/1812.00155)

##### PDF
[http://arxiv.org/pdf/1812.00155](http://arxiv.org/pdf/1812.00155)

