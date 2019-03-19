---
layout: post
title: "EV-IMO: Motion Segmentation Dataset and Learning Pipeline for Event Cameras"
date: 2019-03-18 15:51:25
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Anton Mitrokhin, Chengxi Ye, Cornelia Fermuller, Yiannis Aloimonos, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first event-based learning approach for motion segmentation in indoor scenes and the first event-based dataset - EV-IMO - which includes accurate pixel-wise motion masks, egomotion and ground truth depth. Our approach is based on an efficient implementation of the SfM learning pipeline using a low parameter neural network architecture on event data. In addition to camera egomotion and a dense depth map, the network estimates pixel-wise independently moving object segmentation and computes per-object 3D translational velocities for moving objects. We also train a shallow network with just 40k parameters, which is able to compute depth and egomotion. 
 Our EV-IMO dataset features 32 minutes of indoor recording with up to 3 fast moving objects simultaneously in the camera field of view. The objects and the camera are tracked by the VICON motion capture system. By 3D scanning the room and the objects, accurate depth map ground truth and pixel-wise object masks are obtained, which are reliable even in poor lighting conditions and during fast motion. We then train and evaluate our learning pipeline on EV-IMO and demonstrate that our approach far surpasses its rivals and is well suited for scene constrained robotics applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07520](http://arxiv.org/abs/1903.07520)

##### PDF
[http://arxiv.org/pdf/1903.07520](http://arxiv.org/pdf/1903.07520)

