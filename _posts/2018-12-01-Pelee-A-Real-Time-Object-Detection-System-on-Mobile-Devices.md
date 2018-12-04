---
layout: post
title: "Pelee: A Real-Time Object Detection System on Mobile Devices"
date: 2018-12-01 00:25:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Robert J. Wang, Xiang Li, Charles X. Ling
mathjax: true
---

* content
{:toc}

##### Abstract
An increasing need of running Convolutional Neural Network (CNN) models on mobile devices with limited computing power and memory resource encourages studies on efficient model design. A number of efficient architectures have been proposed in recent years, for example, MobileNet, ShuffleNet, and MobileNetV2. However, all these models are heavily dependent on depthwise separable convolution which lacks efficient implementation in most deep learning frameworks. In this study, we propose an efficient architecture named PeleeNet, which is built with conventional convolution instead. On ImageNet ILSVRC 2012 dataset, our proposed PeleeNet achieves a higher accuracy and over 1.8 times faster speed than MobileNet and MobileNetV2 on NVIDIA TX2. Meanwhile, PeleeNet is only 66% of the model size of MobileNet. We then propose a real-time object detection system by combining PeleeNet with Single Shot MultiBox Detector (SSD) method and optimizing the architecture for fast speed. Our proposed detection system2, named Pelee, achieves 76.4% mAP (mean average precision) on PASCAL VOC2007 and 22.4 mAP on MS COCO dataset at the speed of 23.6 FPS on iPhone 8 and 125 FPS on NVIDIA TX2. The result on COCO outperforms YOLOv2 in consideration of a higher precision, 13.6 times lower computational cost and 11.3 times smaller model size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.06882](http://arxiv.org/abs/1804.06882)

##### PDF
[http://arxiv.org/pdf/1804.06882](http://arxiv.org/pdf/1804.06882)

