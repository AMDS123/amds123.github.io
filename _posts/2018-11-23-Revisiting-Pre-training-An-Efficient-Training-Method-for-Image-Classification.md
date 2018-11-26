---
layout: post
title: "Revisiting Pre-training: An Efficient Training Method for Image Classification"
date: 2018-11-23 02:49:47
categories: arXiv_AI
tags: arXiv_AI Object_Detection Knowledge Segmentation Pose_Estimation Image_Classification Classification Detection
author: Bowen Cheng, Yunchao Wei, Honghui Shi, Shiyu Chang, Jinjun Xiong, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
The training method of repetitively feeding all samples into a pre-defined network for image classification has been widely adopted by current state-of-the-art. In this work, we provide a new method, which can be leveraged to train classification networks in a more efficient way. Starting with a warm-up step, we propose to continually repeat a Drop-and-Pick (DaP) learning strategy. In particular, we drop those easy samples to encourage the network to focus on studying hard ones. Meanwhile, by picking up all samples periodically during training, we aim to recall the memory of the networks to prevent catastrophic forgetting of previously learned knowledge. Our DaP learning method can recover 99.88%, 99.60%, 99.83% top-1 accuracy on ImageNet for ResNet-50, DenseNet-121, and MobileNet-V1 but only requires 75% computation in training compared to those using the classic training schedule. Furthermore, our pre-trained models are equipped with strong knowledge transferability when used for downstream tasks, especially for hard cases. Extensive experiments on object detection, instance segmentation and pose estimation can well demonstrate the effectiveness of our DaP training method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09347](http://arxiv.org/abs/1811.09347)

##### PDF
[http://arxiv.org/pdf/1811.09347](http://arxiv.org/pdf/1811.09347)

