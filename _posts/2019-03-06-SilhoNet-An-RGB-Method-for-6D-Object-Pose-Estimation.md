---
layout: post
title: "SilhoNet: An RGB Method for 6D Object Pose Estimation"
date: 2019-03-06 08:35:33
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Gideon Billings, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous robot manipulation involves estimating the pose of the object to be manipulated. Methods using RGB-D data have shown great success in solving this problem. However, there are situations where cost constraints or the working environment may limit the use of RGB-D sensors. When limited to monocular camera data only, the problem of object pose estimation is very challenging. In this work, we introduce a novel method called SilhoNet that predicts 6D object pose from monocular images. We use a Convolutional Neural Network (CNN) pipeline that takes in region of interest proposals to simultaneously predict an intermediate silhouette representation for objects with an associated occlusion mask and a 3D translation vector. The 3D orientation is then regressed from the predicted silhouettes. We show that our method achieves better overall performance than the state-of-the art PoseCNN network for 6D pose estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06893](http://arxiv.org/abs/1809.06893)

##### PDF
[http://arxiv.org/pdf/1809.06893](http://arxiv.org/pdf/1809.06893)

