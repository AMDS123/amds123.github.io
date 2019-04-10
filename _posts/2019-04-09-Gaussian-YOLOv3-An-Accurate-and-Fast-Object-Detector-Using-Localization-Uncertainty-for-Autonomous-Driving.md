---
layout: post
title: "Gaussian YOLOv3: An Accurate and Fast Object Detector Using Localization Uncertainty for Autonomous Driving"
date: 2019-04-09 12:23:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Jiwoong Choi, Dayoung Chun, Hyun Kim, Hyuk-Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
The use of object detection algorithms is becoming increasingly important in autonomous vehicles, and object detection at high accuracy and a fast inference speed is essential for safe autonomous driving. A false positive (FP) from a false localization during autonomous driving can lead to fatal accidents and hinder safe and efficient driving. Therefore, a detection algorithm that can cope with mislocalizations is required in autonomous driving applications. This paper proposes a method for improving the detection accuracy while supporting a real-time operation by modeling the bounding box (bbox) of YOLOv3, which is the most representative of one-stage detectors, with a Gaussian parameter and redesigning the loss function. In addition, this paper proposes a method for predicting the localization uncertainty that indicates the reliability of bbox. By using the predicted localization uncertainty during the detection process, the proposed schemes can significantly reduce the FP and increase the true positive (TP), thereby improving the accuracy. Compared to a conventional YOLOv3, the proposed algorithm, Gaussian YOLOv3, improves the mean average precision (mAP) by 3.09 and 3.5 on the KITTI and Berkeley deep drive (BDD) datasets, respectively. In addition, on the same datasets, the proposed algorithm can reduce the FP by 41.40% and 40.62%, and increase the TP by 7.26% and 4.3%, respectively. Nevertheless, the proposed algorithm is capable of real-time detection at faster than 42 frames per second (fps).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04620](http://arxiv.org/abs/1904.04620)

##### PDF
[http://arxiv.org/pdf/1904.04620](http://arxiv.org/pdf/1904.04620)

