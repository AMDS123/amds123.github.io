---
layout: post
title: "3D Bounding Box Estimation for Autonomous Vehicles by Cascaded Geometric Constraints and Depurated 2D Detections Using 3D Results"
date: 2019-09-01 11:50:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Classification Detection
author: Jiaojiao Fang, Lingtao Zhou, Guizhong Liu
mathjax: true
---

* content
{:toc}

##### Abstract
3D object detection is one of the most important tasks in 3D vision perceptual system of autonomous vehicles. In this paper, we propose a novel two stage 3D object detection method aimed at get the optimal solution of object location in 3D space based on regressing two additional 3D object properties by a deep convolutional neural network and combined with cascaded geometric constraints between the 2D and 3D boxes. First, we modify the existing 3D properties regressing network by adding two additional components, viewpoints classification and the center projection of the 3D bounding box s bottom face. Second, we use the predicted center projection combined with similar triangle constraint to acquire an initial 3D bounding box by a closed-form solution. Then, the location predicted by previous step is used as the initial value of the over-determined equations constructed by 2D and 3D boxes fitting constraint with the configuration determined with the classified viewpoint. Finally, we use the recovered physical world information by the 3D detections to filter out the false detection and false alarm in 2D detections. We compare our method with the state-of-the-arts on the KITTI dataset show that although conceptually simple, our method outperforms more complex and computational expensive methods not only by improving the overall precision of 3D detections, but also increasing the orientation estimation precision. Furthermore our method can deal with the truncated objects to some extent and remove the false alarm and false detections in both 2D and 3D detections.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01867](http://arxiv.org/abs/1909.01867)

##### PDF
[http://arxiv.org/pdf/1909.01867](http://arxiv.org/pdf/1909.01867)

