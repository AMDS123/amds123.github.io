---
layout: post
title: "Nose, eyes and ears: Head pose estimation by locating facial keypoints"
date: 2018-12-03 14:04:04
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation CNN Deep_Learning
author: Aryaman Gupta, Kalpit Thakkar, Vineet Gandhi, P J Narayanan
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular head pose estimation requires learning a model that computes the intrinsic Euler angles for pose (yaw, pitch, roll) from an input image of human face. Annotating ground truth head pose angles for images in the wild is difficult and requires ad-hoc fitting procedures (which provides only coarse and approximate annotations). This highlights the need for approaches which can train on data captured in controlled environment and generalize on the images in the wild (with varying appearance and illumination of the face). Most present day deep learning approaches which learn a regression function directly on the input images fail to do so. To this end, we propose to use a higher level representation to regress the head pose while using deep learning architectures. More specifically, we use the uncertainty maps in the form of 2D soft localization heatmap images over five facial keypoints, namely left ear, right ear, left eye, right eye and nose, and pass them through an convolutional neural network to regress the head-pose. We show head pose estimation results on two challenging benchmarks BIWI and AFLW and our approach surpasses the state of the art on both the datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00739](http://arxiv.org/abs/1812.00739)

##### PDF
[http://arxiv.org/pdf/1812.00739](http://arxiv.org/pdf/1812.00739)

