---
layout: post
title: "Real-time Joint Object Detection and Semantic Segmentation Network for Automated Driving"
date: 2019-01-12 22:25:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection SLAM
author: Ganesh Sistu, Isabelle Leang, Senthil Yogamani
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) are successfully used for various visual perception tasks including bounding box object detection, semantic segmentation, optical flow, depth estimation and visual SLAM. Generally these tasks are independently explored and modeled. In this paper, we present a joint multi-task network design for learning object detection and semantic segmentation simultaneously. The main motivation is to achieve real-time performance on a low power embedded SOC by sharing of encoder for both the tasks. We construct an efficient architecture using a small ResNet10 like encoder which is shared for both decoders. Object detection uses YOLO v2 like decoder and semantic segmentation uses FCN8 like decoder. We evaluate the proposed network in two public datasets (KITTI, Cityscapes) and in our private fisheye camera dataset, and demonstrate that joint network provides the same accuracy as that of separate networks. We further optimize the network to achieve 30 fps for 1280x384 resolution image.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03912](http://arxiv.org/abs/1901.03912)

##### PDF
[http://arxiv.org/pdf/1901.03912](http://arxiv.org/pdf/1901.03912)

