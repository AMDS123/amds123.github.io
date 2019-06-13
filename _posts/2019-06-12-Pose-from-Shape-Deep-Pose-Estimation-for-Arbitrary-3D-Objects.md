---
layout: post
title: "Pose from Shape: Deep Pose Estimation for Arbitrary 3D Objects"
date: 2019-06-12 12:58:21
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Yang Xiao, Xuchong Qiu, Pierre-Alain Langlois, Mathieu Aubry, Renaud Marlet
mathjax: true
---

* content
{:toc}

##### Abstract
Most deep pose estimation methods need to be trained for specific object instances or categories. In this work we propose a completely generic deep pose estimation approach, which does not require the network to have been trained on relevant categories, nor objects in a category to have a canonical pose. We believe this is a crucial step to design robotic systems that can interact with new objects in the wild not belonging to a predefined category. Our main insight is to dynamically condition pose estimation with a representation of the 3D shape of the target object. More precisely, we train a Convolutional Neural Network that takes as input both a test image and a 3D model, and outputs the relative 3D pose of the object in the input image with respect to the 3D model. We demonstrate that our method boosts performances for supervised category pose estimation on standard benchmarks, namely Pascal3D+, ObjectNet3D and Pix3D, on which we provide results superior to the state of the art. More importantly, we show that our network trained on everyday man-made objects from ShapeNet generalizes without any additional training to completely new types of 3D objects by providing results on the LINEMOD dataset as well as on natural entities such as animals from ImageNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05105](http://arxiv.org/abs/1906.05105)

##### PDF
[http://arxiv.org/pdf/1906.05105](http://arxiv.org/pdf/1906.05105)

