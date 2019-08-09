---
layout: post
title: "Improving the Accuracy of Stereo Visual Odometry Using Visual Illumination Estimation"
date: 2019-08-08 13:17:36
categories: arXiv_CV
tags: arXiv_CV CNN
author: Lee Clement, Valentin Peretroukhin, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
In the absence of reliable and accurate GPS, visual odometry (VO) has emerged as an effective means of estimating the egomotion of robotic vehicles. Like any dead-reckoning technique, VO suffers from unbounded accumulation of drift error over time, but this accumulation can be limited by incorporating absolute orientation information from, for example, a sun sensor. In this paper, we leverage recent work on visual outdoor illumination estimation to show that estimation error in a stereo VO pipeline can be reduced by inferring the sun position from the same image stream used to compute VO, thereby gaining the benefits of sun sensing without requiring a dedicated sun sensor or the sun to be visible to the camera. We compare sun estimation methods based on hand-crafted visual cues and Convolutional Neural Networks (CNNs) and demonstrate our approach on a combined 7.8 km of urban driving from the popular KITTI dataset, achieving up to a 43% reduction in translational average root mean squared error (ARMSE) and a 59% reduction in final translational drift error compared to pure VO alone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1609.04705](http://arxiv.org/abs/1609.04705)

##### PDF
[http://arxiv.org/pdf/1609.04705](http://arxiv.org/pdf/1609.04705)

