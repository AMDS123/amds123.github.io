---
layout: post
title: "A unified neural network for object detection, multiple object tracking and vehicle re-identification"
date: 2019-07-08 09:07:22
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Tracking Object_Tracking Inference Detection
author: Yuhao Xu, Jiakui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep SORT\cite{wojke2017simple} is a tracking-by-detetion approach to multiple object tracking with a detector and a RE-ID model. 
 Both separately training and inference with the two model is time-comsuming. 
 In this paper, we unify the detector and RE-ID model into an end-to-end network, by adding an additional track branch for tracking in Faster RCNN architecture. With a unified network, we are able to train the whole model end-to-end with multi loss, which has shown much benefit in other recent works. 
 The RE-ID model in Deep SORT needs to use deep CNNs to extract feature map from detected object images, However, track branch in our proposed network straight make use of 
 the RoI feature vector in Faster RCNN baseline, which reduced the amount of calculation. 
 Since the single image lacks the same object which is necessary when we use the triplet loss to optimizer the track branch, we concatenate the neighbouring frames in a video to construct our training dataset. 
 We have trained and evaluated our model on AIC19 vehicle tracking dataset, experiment shows that our model with resnet101 backbone can achieve 57.79 \% mAP and track vehicle well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03465](http://arxiv.org/abs/1907.03465)

##### PDF
[http://arxiv.org/pdf/1907.03465](http://arxiv.org/pdf/1907.03465)

