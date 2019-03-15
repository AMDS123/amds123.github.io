---
layout: post
title: "Learning Orientation-Estimation Convolutional Neural Network for Building Detection in Optical Remote Sensing Image"
date: 2019-03-14 09:02:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Deep_Learning Detection
author: Yongliang Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Benefiting from the great success of deep learning in computer vision, CNN-based object detection methods have drawn significant attentions. Various frameworks have been proposed which show awesome and robust performance for a large range of datasets. However, for building detection in remote sensing images, buildings always pose a diversity of orientations which makes it a challenge for the application of off-the-shelf methods to building detection. In this work, we aim to integrate orientation regression into the popular axis-aligned bounding-box detection method to tackle this problem. To adapt the axis-aligned bounding boxes to arbitrarily orientated ones, we also develop an algorithm to estimate the Intersection over Union (IoU) overlap between any two arbitrarily oriented boxes which is convenient to implement in Graphics Processing Unit (GPU) for accelerating computation. The proposed method utilizes CNN for both robust feature extraction and rotated bounding box regression. We present our modelin an end-to-end fashion making it easy to train. The model is formulated and trained to predict orientation, location and extent simultaneously obtaining tighter bounding box and hence, higher mean average precision (mAP). Experiments on remote sensing images of different scales shows a promising performance over the conventional one.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05862](http://arxiv.org/abs/1903.05862)

##### PDF
[http://arxiv.org/pdf/1903.05862](http://arxiv.org/pdf/1903.05862)

