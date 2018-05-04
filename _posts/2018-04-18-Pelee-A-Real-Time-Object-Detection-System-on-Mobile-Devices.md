---
layout: post
title: "Pelee: A Real-Time Object Detection System on Mobile Devices"
date: 2018-04-18 19:27:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Robert J. Wang, Xiang Li, Shuang Ao, Charles X. Ling
mathjax: true
---

* content
{:toc}

##### Abstract
An increasing need of running Convolutional Neural Network (CNN) models on mobile devices with limited computing power and memory resource encourages studies on efficient model design. A number of efficient architectures have been proposed in recent years, for example, MobileNet, ShuffleNet, and NASNet-A. However, all these models are heavily dependent on depthwise separable convolution which lacks efficient implementation in most deep learning frameworks. In this study, we propose an efficient architecture named PeleeNet, which is built with conventional convolution instead. On ImageNet ILSVRC 2012 dataset, our proposed PeleeNet achieves a higher accuracy by 0.6% (71.3% vs. 70.7%) and 11% lower computational cost than MobileNet, the state-of-the-art efficient architecture. Meanwhile, PeleeNet is only 66% of the model size of MobileNet. We then propose a real-time object detection system by combining PeleeNet with Single Shot MultiBox Detector (SSD) method and optimizing the architecture for fast speed. Our proposed detection system, named Pelee, achieves 76.4% mAP (mean average precision) on PASCAL VOC2007 and 22.4 mAP on MS COCO dataset at the speed of 17.1 FPS on iPhone 6s and 23.6 FPS on iPhone 8. The result on COCO outperforms YOLOv2 in consideration of a higher precision, 13.6 times lower computational cost and 11.3 times smaller model size. The code and models are open sourced.

##### Abstract (translated by Google)
在计算能力和内存资源有限的移动设备上运行卷积神经网络（CNN）模型的需求日益增加，这促使人们研究有效的模型设计。近年来已提出了许多有效的体系结构，例如MobileNet，ShuffleNet和NASNet-A。然而，所有这些模型严重依赖于深度可分卷积，在大多数深度学习框架中缺乏有效的实现。在这项研究中，我们提出了一个名为PeleeNet的高效架构，它是用常规卷积代替的。在ImageNet ILSVRC 2012数据集中，我们提出的PeleeNet比MobileNet这种最先进的高效架构的准确度高0.6％（71.3％比70.7％）和计算成本低11％。同时，PeleeNet仅为MobileNet模型尺寸的66％。然后，我们通过将PeleeNet与Single Shot MultiBox Detector（SSD）方法相结合，并针对快速速度优化体系结构，提出了一种实时对象检测系统。我们建议的检测系统名为Pelee，在PASCAL VOC2007和MS COCO数据集上分别达到76.4％的mAP（平均精确度）和17.4 FPS的iPhone 6和23.6 FPS。在COCO上的结果优于YOLOv2 in考虑更高的精度，13.6倍的低计算成本和11.3倍的模型尺寸。代码和模型是开源的。

##### URL
[https://arxiv.org/abs/1804.06882](https://arxiv.org/abs/1804.06882)

##### PDF
[https://arxiv.org/pdf/1804.06882](https://arxiv.org/pdf/1804.06882)

