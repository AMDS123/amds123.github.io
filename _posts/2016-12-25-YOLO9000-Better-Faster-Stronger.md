---
layout: post
title: "YOLO9000: Better, Faster, Stronger"
date: 2016-12-25 07:21:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Joseph Redmon, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce YOLO9000, a state-of-the-art, real-time object detection system that can detect over 9000 object categories. First we propose various improvements to the YOLO detection method, both novel and drawn from prior work. The improved model, YOLOv2, is state-of-the-art on standard detection tasks like PASCAL VOC and COCO. At 67 FPS, YOLOv2 gets 76.8 mAP on VOC 2007. At 40 FPS, YOLOv2 gets 78.6 mAP, outperforming state-of-the-art methods like Faster RCNN with ResNet and SSD while still running significantly faster. Finally we propose a method to jointly train on object detection and classification. Using this method we train YOLO9000 simultaneously on the COCO detection dataset and the ImageNet classification dataset. Our joint training allows YOLO9000 to predict detections for object classes that don't have labelled detection data. We validate our approach on the ImageNet detection task. YOLO9000 gets 19.7 mAP on the ImageNet detection validation set despite only having detection data for 44 of the 200 classes. On the 156 classes not in COCO, YOLO9000 gets 16.0 mAP. But YOLO can detect more than just 200 classes; it predicts detections for more than 9000 different object categories. And it still runs in real-time.

##### Abstract (translated by Google)
我们引入了一个先进的实时对象检测系统YOLO9000，可以检测超过9000个对象类别。首先，我们提出了对YOLO检测方法的各种改进，既有新颖性，也有前期的工作。改进后的模型YOLOv2在PASCAL VOC和COCO等标准检测任务上是最先进的。在67 FPS时，YOLOv2在VOC 2007上获得了76.8 mAP。在40 FPS下，YOLOv2获得了78.6 mAP，比ResNet和SSD的更快的RCNN等先进方法性能更出色，同时运行速度更快。最后提出了一种联合训练目标检测与分类的方法。使用这种方法，我们在COCO检测数据集和ImageNet分类数据集上同时训练YOLO9000。我们的联合培训允许YOLO9000预测未标注检测数据的对象类别的检测结果。我们在ImageNet检测任务上验证了我们的方法。 YOLO9000在ImageNet检测验证集上获得19.7 mAP，尽管只有200个类别中有44个具有检测数据。在没有COCO的156班上，YOLO9000获得16.0 mAP。但是YOLO可以检测到200多个班级。它预测超过9000个不同的对象类别的检测。它仍然在实时运行。

##### URL
[https://arxiv.org/abs/1612.08242](https://arxiv.org/abs/1612.08242)

##### PDF
[https://arxiv.org/pdf/1612.08242](https://arxiv.org/pdf/1612.08242)

