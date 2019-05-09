---
layout: post
title: "Training a Fast Object Detector for LiDAR Range Images Using Labeled Data from Sensors with Higher Resolution"
date: 2019-05-08 13:43:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Manuel Herzog, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an efficient model for object detection from LiDAR sensors in self-driving cars and a strategy to train the model using data from a different type of LiDAR sensor. Currently, the highest performing algorithms for object detection from LiDAR measurements are based on neural networks. Training these networks using supervised learning requires large annotated datasets. This has led to the situation that most research using neural networks for object detection from LiDAR point clouds is done on a very small number of publicly available datasets and a very small number of sensor types. This paper uses an existing annotated dataset to train a neural network that can be used with a LiDAR sensor that has a lower resolution than the one used for recording the annotated dataset. This is done by simulating data from the lower resolution LiDAR sensor based on the higher resolution dataset. Furthermore, improvements to models that use LiDAR range images for object detection are presented. The results are validated both on simulated sensor data and on data from an actual lower resolution sensor mounted to a research vehicle. It is shown, that the model can predict objects from 360{\deg} range images in real time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03066](http://arxiv.org/abs/1905.03066)

##### PDF
[http://arxiv.org/pdf/1905.03066](http://arxiv.org/pdf/1905.03066)

