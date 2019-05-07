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


##### URL
[https://arxiv.org/abs/1705.09587](https://arxiv.org/abs/1705.09587)

##### PDF
[https://arxiv.org/pdf/1705.09587](https://arxiv.org/pdf/1705.09587)

