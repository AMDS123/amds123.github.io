---
layout: post
title: "DAC: Data-free Automatic Acceleration of Convolutional Networks"
date: 2018-12-20 06:26:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Image_Classification Classification Deep_Learning Detection
author: Xin Li, Shuai Zhang, Bolan Jiang, Yingyong Qi, Mooi Choo Chuah, Ning Bi
mathjax: true
---

* content
{:toc}

##### Abstract
Deploying a deep learning model on mobile/IoT devices is a challenging task. The difficulty lies in the trade-off between computation speed and accuracy. A complex deep learning model with high accuracy runs slowly on resource-limited devices, while a light-weight model that runs much faster loses accuracy. In this paper, we propose a novel decomposition method, namely DAC, that is capable of factorizing an ordinary convolutional layer into two layers with much fewer parameters. DAC computes the corresponding weights for the newly generated layers directly from the weights of the original convolutional layer. Thus, no training (or fine-tuning) or any data is needed. The experimental results show that DAC reduces a large number of floating-point operations (FLOPs) while maintaining high accuracy of a pre-trained model. If 2% accuracy drop is acceptable, DAC saves 53% FLOPs of VGG16 image classification model on ImageNet dataset, 29% FLOPS of SSD300 object detection model on PASCAL VOC2007 dataset, and 46% FLOPS of a multi-person pose estimation model on Microsoft COCO dataset. Compared to other existing decomposition methods, DAC achieves better performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.08374](https://arxiv.org/abs/1812.08374)

##### PDF
[https://arxiv.org/pdf/1812.08374](https://arxiv.org/pdf/1812.08374)

