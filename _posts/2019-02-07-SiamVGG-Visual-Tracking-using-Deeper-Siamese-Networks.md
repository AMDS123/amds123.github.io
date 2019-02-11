---
layout: post
title: "SiamVGG: Visual Tracking using Deeper Siamese Networks"
date: 2019-02-07 19:08:34
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Relation
author: Yuhong Li, Xiaofan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, we have seen a rapid development of Deep Neural Network (DNN) based visual tracking solutions. Some trackers combine the DNN-based solutions with Discriminative Correlation Filters (DCF) to extract semantic features and successfully deliver the state-of-the-art tracking accuracy. However, these solutions are highly compute-intensive, which require long processing time, resulting unsecured real-time performance. To deliver both high accuracy and reliable real-time performance, we propose a novel tracker called SiamVGG. It combines a Convolutional Neural Network (CNN) backbone and a cross-correlation operator, and takes advantage of the features from exemplary images for more accurate object tracking. 
 The architecture of SiamVGG is customized from VGG-16, with the parameters shared by both exemplary images and desired input video frames. 
 We demonstrate the proposed SiamVGG on OTB-2013/50/100 and VOT 2015/2016/2017 datasets with the state-of-the-art accuracy while maintaining a decent real-time performance of 50 FPS running on a GTX 1080Ti. Our design can achieve 2% higher Expected Average Overlap (EAO) compared to the ECO and C-COT in VOT2017 Challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02804](http://arxiv.org/abs/1902.02804)

##### PDF
[http://arxiv.org/pdf/1902.02804](http://arxiv.org/pdf/1902.02804)

