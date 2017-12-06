---
layout: post
title: "Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks"
date: 2016-01-06 06:30:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Shaoqing Ren, Kaiming He, Ross Girshick, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art object detection networks depend on region proposal algorithms to hypothesize object locations. Advances like SPPnet and Fast R-CNN have reduced the running time of these detection networks, exposing region proposal computation as a bottleneck. In this work, we introduce a Region Proposal Network (RPN) that shares full-image convolutional features with the detection network, thus enabling nearly cost-free region proposals. An RPN is a fully convolutional network that simultaneously predicts object bounds and objectness scores at each position. The RPN is trained end-to-end to generate high-quality region proposals, which are used by Fast R-CNN for detection. We further merge RPN and Fast R-CNN into a single network by sharing their convolutional features---using the recently popular terminology of neural networks with 'attention' mechanisms, the RPN component tells the unified network where to look. For the very deep VGG-16 model, our detection system has a frame rate of 5fps (including all steps) on a GPU, while achieving state-of-the-art object detection accuracy on PASCAL VOC 2007, 2012, and MS COCO datasets with only 300 proposals per image. In ILSVRC and COCO 2015 competitions, Faster R-CNN and RPN are the foundations of the 1st-place winning entries in several tracks. Code has been made publicly available.

##### Abstract (translated by Google)
最先进的物体检测网络依靠区域提议算法来假设物体的位置。像SPPnet和Fast R-CNN这样的进步减少了这些检测网络的运行时间，使得区域提议计算成为一个瓶颈。在这项工作中，我们引入了一个区域提议网络（RPN），该网络与检测网络共享全图像卷积特征，从而使近乎成本的区域提议成为可能。 RPN是一个完全卷积网络，可以同时预测每个位置的对象边界和对象分数。 RPN经过端到端的训练，生成高质量的区域提案，由Fast R-CNN用于检测。我们进一步将RPN和Fast R-CNN融合到一个网络中，通过共享其卷积特征---使用最近流行的神经网络术语“注意”机制，RPN组件告诉统一网络在哪里寻找。对于非常深的VGG-16型号，我们的检测系统在GPU上的帧频为5fps（包括所有步骤），同时在PASCAL VOC 2007,2012和MS COCO数据集上实现了最新的目标检测精度每张图片只有300个提案。在ILSVRC和COCO 2015比赛中，更快的R-CNN和RPN是多条赛道中获得第一名的基础。代码已经公开。

##### URL
[https://arxiv.org/abs/1506.01497](https://arxiv.org/abs/1506.01497)

