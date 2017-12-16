---
layout: post
title: "Improving Sonar Image Patch Matching via Deep Learning"
date: 2017-09-07 09:25:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Classification Deep_Learning Detection SLAM Recognition
author: Matias Valdenegro-Toro
mathjax: true
---

* content
{:toc}

##### Abstract
Matching sonar images with high accuracy has been a problem for a long time, as sonar images are inherently hard to model due to reflections, noise and viewpoint dependence. Autonomous Underwater Vehicles require good sonar image matching capabilities for tasks such as tracking, simultaneous localization and mapping (SLAM) and some cases of object detection/recognition. We propose the use of Convolutional Neural Networks (CNN) to learn a matching function that can be trained from labeled sonar data, after pre-processing to generate matching and non-matching pairs. In a dataset of 39K training pairs, we obtain 0.91 Area under the ROC Curve (AUC) for a CNN that outputs a binary classification matching decision, and 0.89 AUC for another CNN that outputs a matching score. In comparison, classical keypoint matching methods like SIFT, SURF, ORB and AKAZE obtain AUC 0.61 to 0.68. Alternative learning methods obtain similar results, with a Random Forest Classifier obtaining AUC 0.79, and a Support Vector Machine resulting in AUC 0.66.

##### Abstract (translated by Google)
高精度匹配的声纳图像一直是个问题，因为声纳图像由于反射，噪声和视点依赖性而固有地难以建模。自主水下飞行器需要良好的声纳图像匹配能力，用于诸如跟踪，同时定位和映射（SLAM）以及一些物体检测/识别的任务。我们提出使用卷积神经网络（CNN）来学习一个匹配函数，可以从预先处理生成匹配和不匹配的对之后，从标记的声纳数据进行训练。在39K训练对的数据集中，对于输出二进制分类匹配决定的CNN，我们获得ROC曲线（AUC）下的0.91面积，以及输出匹配分数的另一CNN的0.89AUC。相比之下，像SIFT，SURF，ORB和AKAZE的经典关键点匹配方法获得AUC 0.61至0.68。替代学习方法获得类似的结果，随机森林分类器获得AUC 0.79，支持向量机，导致AUC 0.66。

##### URL
[https://arxiv.org/abs/1709.02150](https://arxiv.org/abs/1709.02150)

##### PDF
[https://arxiv.org/pdf/1709.02150](https://arxiv.org/pdf/1709.02150)

