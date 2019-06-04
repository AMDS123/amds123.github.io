---
layout: post
title: "Efficient Object Detection Model for Real-Time UAV Applications"
date: 2019-05-30 20:24:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Drone CNN Inference Detection
author: Subrahmanyam Vaddi, Chandan Kumar, Ali Jannesari
mathjax: true
---

* content
{:toc}

##### Abstract
Unmanned Aerial Vehicles (UAVs) especially drones, equipped with vision techniques have become very popular in recent years, with their extensive use in wide range of applications. Many of these applications require use of computer vision techniques, particularly object detection from the information captured by on-board camera. In this paper, we propose an end to end object detection model running on a UAV platform which is suitable for real-time applications. We propose a deep feature pyramid architecture which makes use of inherent properties of features extracted from Convolutional Networks by capturing more generic features in the images (such as edge, color etc.) along with the minute detailed features specific to the classes contained in our problem. We use VisDrone-18 dataset for our studies which contain different objects such as pedestrians, vehicles, bicycles etc. We provide software and hardware architecture of our platform used in this study. We implemented our model with both ResNet and MobileNet as convolutional bases. Our model combined with modified focal loss function, produced a desirable performance of 30.6 mAP for object detection with an inference time of 14 fps. We compared our results with RetinaNet-ResNet-50 and HAL-RetinaNet and shown that our model combined with MobileNet as backend feature extractor gave the best results in terms of accuracy, speed and memory efficiency and is best suitable for real time object detection with drones.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00786](http://arxiv.org/abs/1906.00786)

##### PDF
[http://arxiv.org/pdf/1906.00786](http://arxiv.org/pdf/1906.00786)

