---
layout: post
title: "Enhancement of SSD by concatenating feature maps for object detection"
date: 2017-05-26 14:07:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jisoo Jeong, Hyojin Park, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an object detection method that improves the accuracy of the conventional SSD (Single Shot Multibox Detector), which is one of the top object detection algorithms in both aspects of accuracy and speed. The performance of a deep network is known to be improved as the number of feature maps increases. However, it is difficult to improve the performance by simply raising the number of feature maps. In this paper, we propose and analyze how to use feature maps effectively to improve the performance of the conventional SSD. The enhanced performance was obtained by changing the structure close to the classifier network, rather than growing layers close to the input data, e.g., by replacing VGGNet with ResNet. The proposed network is suitable for sharing the weights in the classifier networks, by which property, the training can be faster with better generalization power. For the Pascal VOC 2007 test set trained with VOC 2007 and VOC 2012 training sets, the proposed network with the input size of 300 x 300 achieved 78.5% mAP (mean average precision) at the speed of 35.0 FPS (frame per second), while the network with a 512 x 512 sized input achieved 80.8% mAP at 16.6 FPS using Nvidia Titan X GPU. The proposed network shows state-of-the-art mAP, which is better than those of the conventional SSD, YOLO, Faster-RCNN and RFCN. Also, it is faster than Faster-RCNN and RFCN.

##### Abstract (translated by Google)
我们提出了一种提高传统SSD（Single Shot Multibox Detector）的精度的物体检测方法，该方法是精度和速度两方面的顶级目标检测算法之一。深度网络的性能已知随着特征映射的数量的增加而改善。但是，通过简单地增加特征图的数量来提高性能是困难的。在本文中，我们提出并分析如何有效地使用特征映射来提高传统SSD的性能。通过改变接近分类器网络的结构而不是靠近输入数据增长层，例如通过用ResNet代替VGGNet来获得增强的性能。所提出的网络适合在分类器网络中共享权值，通过该权值，训练速度更快，泛化能力更强。对于使用VOC 2007和VOC 2012训练集训练的Pascal VOC 2007测试集，建议的输入尺寸为300 x 300的网络以35.0 FPS（帧/秒）的速度达到78.5％的mAP（平均精度），而采用Nvidia Titan X GPU的512 x 512尺寸输入的网络以16.6 FPS达到了80.8％的mAP。提出的网络显示了最先进的MAP，比传统的SSD，YOLO，Faster-RCNN和RFCN更好。而且，它比Faster-RCNN和RFCN更快。

##### URL
[https://arxiv.org/abs/1705.09587](https://arxiv.org/abs/1705.09587)

