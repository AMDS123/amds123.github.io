---
layout: post
title: "DSCnet: Replicating Lidar Point Clouds with Deep Sensor Cloning"
date: 2018-11-17 01:03:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Classification Prediction Detection
author: Paden Tomasello, Sammy Sidhu, Anting Shen, Matthew W. Moskewicz, Nobie Redmon, Gataryi Joshi, Romi Phadte, Paras Jain, Forrest Iandola
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have become increasingly popular for solving a variety of computer vision tasks, ranging from image classification to image segmentation. Recently, autonomous vehicles have created a demand for depth information, which is often obtained using hardware sensors such as Light detection and ranging (LIDAR). Although it can provide precise distance measurements, most LIDARs are still far too expensive to sell in mass-produced consumer vehicles, which has motivated methods to generate depth information from commodity automotive sensors like cameras. 
 In this paper, we propose an approach called Deep Sensor Cloning (DSC). The idea is to use Convolutional Neural Networks in conjunction with inexpensive sensors to replicate the 3D point-clouds that are created by expensive LIDARs. To accomplish this, we develop a new dataset (DSDepth) and a new family of CNN architectures (DSCnets). While previous tasks such as KITTI depth prediction use an interpolated RGB-D images as ground-truth for training, we instead use DSCnets to directly predict LIDAR point-clouds. When we compare the output of our models to a $75,000 LIDAR, we find that our most accurate DSCnet achieves a relative error of 5.77% using a single camera and 4.69% using stereo cameras.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07070](http://arxiv.org/abs/1811.07070)

##### PDF
[http://arxiv.org/pdf/1811.07070](http://arxiv.org/pdf/1811.07070)

