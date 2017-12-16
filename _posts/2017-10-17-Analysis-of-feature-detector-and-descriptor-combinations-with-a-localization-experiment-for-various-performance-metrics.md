---
layout: post
title: "Analysis of feature detector and descriptor combinations with a localization experiment for various performance metrics"
date: 2017-10-17 12:10:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Ertugrul Bayraktar, Pinar Boyraz
mathjax: true
---

* content
{:toc}

##### Abstract
The purpose of this study is to provide a detailed performance comparison of feature detector/descriptor methods, particularly when their various combinations are used for image-matching. The localization experiments of a mobile robot in an indoor environment are presented as a case study. In these experiments, 3090 query images and 127 dataset images were used. This study includes five methods for feature detectors (features from accelerated segment test (FAST), oriented FAST and rotated binary robust independent elementary features (BRIEF) (ORB), speeded-up robust features (SURF), scale invariant feature transform (SIFT), and binary robust invariant scalable keypoints (BRISK)) and five other methods for feature descriptors (BRIEF, BRISK, SIFT, SURF, and ORB). These methods were used in 23 different combinations and it was possible to obtain meaningful and consistent comparison results using the performance criteria defined in this study. All of these methods were used independently and separately from each other as either feature detector or descriptor. The performance analysis shows the discriminative power of various combinations of detector and descriptor methods. The analysis is completed using five parameters: (i) accuracy, (ii) time, (iii) angle difference between keypoints, (iv) number of correct matches, and (v) distance between correctly matched keypoints. In a range of 60{\deg}, covering five rotational pose points for our system, the FAST-SURF combination had the lowest distance and angle difference values and the highest number of matched keypoints. SIFT-SURF was the most accurate combination with a 98.41% correct classification rate. The fastest algorithm was ORB-BRIEF, with a total running time of 21,303.30 s to match 560 images captured during motion with 127 dataset images.

##### Abstract (translated by Google)
本研究的目的是提供特征检测器/描述符方法的详细性能比较，特别是当它们的各种组合用于图像匹配时。本文以移动机器人在室内环境下的定位实验为例，在这些实验中，使用了3090个查询图像和127个数据集图像。 （FAST），面向FAST和旋转二进制鲁棒独立基本特征（BRIEF）（ORB），加速鲁棒特征（SURF），尺度不变特征变换（SIFT）等五种特征检测方法。 （BRISK））和其他五种特征描述符（BRIEF，BRISK，SIFT，SURF和ORB）的方法。这些方法被用于23种不同的组合，并有可能使用本研究中定义的性能标准来获得有意义和一致的比较结果。所有这些方法被独立使用，并且彼此分开作为特征检测器或描述符。性能分析显示了检测器和描述符方法各种组合的判别能力。 （i）准确度，（ii）时间，（iii）关键点之间的角度差异，（iv）正确匹配的数目，以及（v）正确匹配的关键点之间的距离来完成分析。在覆盖我们系统的五个旋转姿态点的60°{\ deg}的范围内，FAST-SURF组合具有最小的距离和角度差值以及最多的匹配关键点。 SIFT-SURF是最准确的组合，正确的分类率为98.41％。最快的算法是ORB-BRIEF，总运行时间为21,303.30秒，以匹配在运动期间捕获的560幅图像与127个数据集图像。

##### URL
[https://arxiv.org/abs/1710.06232](https://arxiv.org/abs/1710.06232)

##### PDF
[https://arxiv.org/pdf/1710.06232](https://arxiv.org/pdf/1710.06232)

