---
layout: post
title: "Pose Estimation for Non-Cooperative Rendezvous Using Neural Networks"
date: 2019-06-24 11:51:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Detection
author: Sumant Sharma, Simone D&#x27;Amico
mathjax: true
---

* content
{:toc}

##### Abstract
This work introduces the Spacecraft Pose Network (SPN) for on-board estimation of the pose, i.e., the relative position and attitude, of a known non-cooperative spacecraft using monocular vision. In contrast to other state-of-the-art pose estimation approaches for spaceborne applications, the SPN method does not require the formulation of hand-engineered features and only requires a single grayscale image to determine the pose of the spacecraft relative to the camera. The SPN method uses a Convolutional Neural Network (CNN) with three branches to solve for the pose. The first branch of the CNN bootstraps a state-of-the-art object detector to detect a 2D bounding box around the target spacecraft. The region inside the bounding box is then used by the other two branches of the CNN to determine the attitude by initially classifying the input region into discrete coarse attitude labels before regressing to a finer estimate. The SPN method then uses a novel Gauss-Newton algorithm to estimate the position by using the constraints imposed by the detected 2D bounding box and the estimated attitude. The secondary contribution of this work is the generation of the Spacecraft PosE Estimation Dataset (SPEED). SPEED consists of synthetic as well as actual camera images of a mock-up of the Tango spacecraft from the PRISMA mission. The synthetic images are created by fusing OpenGL-based renderings of the spacecraft's 3D model with actual images of the Earth captured by the Himawari-8 meteorological satellite. The actual camera images are created using a 7 degrees-of-freedom robotic arm, which positions and orients a vision-based sensor with respect to a full-scale mock-up of the Tango spacecraft. The SPN method, trained only on synthetic images, produces degree-level attitude error and cm-level position errors when evaluated on the actual camera images not used during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09868](http://arxiv.org/abs/1906.09868)

##### PDF
[http://arxiv.org/pdf/1906.09868](http://arxiv.org/pdf/1906.09868)

