---
layout: post
title: "SlimYOLOv3: Narrower, Faster and Better for Real-Time UAV Applications"
date: 2019-07-25 14:22:43
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Drone CNN Detection
author: Pengyi Zhang, Yunxin Zhong, Xiaoqiong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Drones or general Unmanned Aerial Vehicles (UAVs), endowed with computer vision function by on-board cameras and embedded systems, have become popular in a wide range of applications. However, real-time scene parsing through object detection running on a UAV platform is very challenging, due to limited memory and computing power of embedded devices. To deal with these challenges, in this paper we propose to learn efficient deep object detectors through channel pruning of convolutional layers. To this end, we enforce channel-level sparsity of convolutional layers by imposing L1 regularization on channel scaling factors and prune less informative feature channels to obtain "slim" object detectors. Based on such approach, we present SlimYOLOv3 with fewer trainable parameters and floating point operations (FLOPs) in comparison of original YOLOv3 (Joseph Redmon et al., 2018) as a promising solution for real-time object detection on UAVs. We evaluate SlimYOLOv3 on VisDrone2018-Det benchmark dataset; compelling results are achieved by SlimYOLOv3 in comparison of unpruned counterpart, including ~90.8% decrease of FLOPs, ~92.0% decline of parameter size, running ~2 times faster and comparable detection accuracy as YOLOv3. Experimental results with different pruning ratios consistently verify that proposed SlimYOLOv3 with narrower structure are more efficient, faster and better than YOLOv3, and thus are more suitable for real-time object detection on UAVs. Our codes are made publicly available at https://github.com/PengyiZhang/SlimYOLOv3.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11093](http://arxiv.org/abs/1907.11093)

##### PDF
[http://arxiv.org/pdf/1907.11093](http://arxiv.org/pdf/1907.11093)

