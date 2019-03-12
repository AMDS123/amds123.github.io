---
layout: post
title: "Domain Randomization for Active Pose Estimation"
date: 2019-03-10 08:33:14
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Xinyi Ren, Jianlan Luo, Eugen Solowjow, Juan Aparicio Ojea, Abhishek Gupta, Aviv Tamar, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate state estimation is a fundamental component of robotic control. In robotic manipulation tasks, as is our focus in this work, state estimation is essential for identifying the positions of objects in the scene, forming the basis of the manipulation plan. However, pose estimation typically requires expensive 3D cameras or additional instrumentation such as fiducial markers to perform accurately. Recently, Tobin et al.~introduced an approach to pose estimation based on domain randomization, where a neural network is trained to predict pose directly from a 2D image of the scene. The network is trained on computer-generated images with a high variation in textures and lighting, thereby generalizing to real-world images. In this work, we investigate how to improve the accuracy of domain randomization based pose estimation. Our main idea is that active perception -- moving the robot to get a better estimate of pose -- can be trained in simulation and transferred to real using domain randomization. In our approach, the robot trains in a domain-randomized simulation how to estimate pose from a \emph{sequence} of images. We show that our approach can significantly improve the accuracy of standard pose estimation in several scenarios: when the robot holding an object moves, when reference objects are moved in the scene, or when the camera is moved around the object.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03953](https://arxiv.org/abs/1903.03953)

##### PDF
[https://arxiv.org/pdf/1903.03953](https://arxiv.org/pdf/1903.03953)

