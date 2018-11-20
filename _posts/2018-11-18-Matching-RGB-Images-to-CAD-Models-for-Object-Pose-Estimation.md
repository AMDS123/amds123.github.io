---
layout: post
title: "Matching RGB Images to CAD Models for Object Pose Estimation"
date: 2018-11-18 00:32:58
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Georgios Georgakis, Srikrishna Karanam, Ziyan Wu, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for 3D object pose estimation in RGB images, which does not require pose annotations of objects in images in the training stage. We tackle the pose estimation problem by learning how to establish correspondences between RGB images and rendered depth images of CAD models. During training, our approach only requires textureless CAD models and aligned RGB-D frames of a subset of object instances, without explicitly requiring pose annotations for the RGB images. We employ a deep quadruplet convolutional neural network for joint learning of suitable keypoints and their associated descriptors in pairs of rendered depth images which can be matched across modalities with aligned RGB-D views. During testing, keypoints are extracted from a query RGB image and matched to keypoints extracted from rendered depth images, followed by establishing 2D-3D correspondences. The object's pose is then estimated using the RANSAC and PnP algorithms. We conduct experiments on the recently introduced Pix3D dataset and demonstrate the efficacy of our proposed approach in object pose estimation as well as generalization to object instances not seen during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07249](http://arxiv.org/abs/1811.07249)

##### PDF
[http://arxiv.org/pdf/1811.07249](http://arxiv.org/pdf/1811.07249)

