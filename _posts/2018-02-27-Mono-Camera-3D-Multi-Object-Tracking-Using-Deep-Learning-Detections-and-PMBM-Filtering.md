---
layout: post
title: "Mono-Camera 3D Multi-Object Tracking Using Deep Learning Detections and PMBM Filtering"
date: 2018-02-27 15:46:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Deep_Learning Detection
author: Samuel Scheidegger, Joachim Benjaminsson, Emil Rosenberg, Amrit Krishnan, Karl Granstrom
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular cameras are one of the most commonly used sensors in the automotive industry for autonomous vehicles. One major drawback using a monocular camera is that it only makes observations in the two dimensional image plane and can not directly measure the distance to objects. In this paper, we aim at filling this gap by developing a multi-object tracking algorithm that takes an image as input and produces trajectories of detected objects in a world coordinate system. We solve this by using a deep neural network trained to detect and estimate the distance to objects from a single input image. The detections from a sequence of images are fed in to a state-of-the art Poisson multi-Bernoulli mixture tracking filter. The combination of the learned detector and the PMBM filter results in an algorithm that achieves 3D tracking using only mono-camera images as input. The performance of the algorithm is evaluated both in 3D world coordinates, and 2D image coordinates, using the publicly available KITTI object tracking dataset. The algorithm shows the ability to accurately track objects, correctly handle data associations, even when there is a big overlap of the objects in the image, and is one of the top performing algorithms on the KITTI object tracking benchmark. Furthermore, the algorithm is efficient, running on average close to 20 frames per second.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.09975](https://arxiv.org/abs/1802.09975)

##### PDF
[https://arxiv.org/pdf/1802.09975](https://arxiv.org/pdf/1802.09975)

