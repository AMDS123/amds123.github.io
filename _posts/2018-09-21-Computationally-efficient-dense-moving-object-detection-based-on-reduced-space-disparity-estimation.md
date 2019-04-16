---
layout: post
title: "Computationally efficient dense moving object detection based on reduced space disparity estimation"
date: 2018-09-21 08:32:46
categories: arXiv_CV
tags: arXiv_CV Semi_Global Object_Detection Prediction Detection
author: Goran Popović, Antea Hadviger, Ivan Marković, Ivan Petrović
mathjax: true
---

* content
{:toc}

##### Abstract
Computationally efficient moving object detection and depth estimation from a stereo camera is an extremely useful tool for many computer vision applications, including robotics and autonomous driving. In this paper we show how moving objects can be densely detected by estimating disparity using an algorithm that improves complexity and accuracy of stereo matching by relying on information from previous frames. The main idea behind this approach is that by using the ego-motion estimation and the disparity map of the previous frame, we can set a prior base that enables us to reduce the complexity of the current frame disparity estimation, subsequently also detecting moving objects in the scene. For each pixel we run a Kalman filter that recursively fuses the disparity prediction and reduced space semi-global matching (SGM) measurements. The proposed algorithm has been implemented and optimized using streaming single instruction multiple data instruction set and multi-threading. Furthermore, in order to estimate the process and measurement noise as reliably as possible, we conduct extensive experiments on the KITTI suite using the ground truth obtained by the 3D laser range sensor. Concerning disparity estimation, compared to the OpenCV SGM implementation, the proposed method yields improvement on the KITTI dataset sequences in terms of both speed and accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.07986](https://arxiv.org/abs/1809.07986)

##### PDF
[https://arxiv.org/pdf/1809.07986](https://arxiv.org/pdf/1809.07986)

