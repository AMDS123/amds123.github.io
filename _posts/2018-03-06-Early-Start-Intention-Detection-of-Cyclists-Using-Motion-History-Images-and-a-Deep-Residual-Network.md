---
layout: post
title: "Early Start Intention Detection of Cyclists Using Motion History Images and a Deep Residual Network"
date: 2018-03-06 15:12:27
categories: arXiv_AI
tags: arXiv_AI CNN Image_Classification Classification Detection
author: Stefan Zernetsch, Viktor Kress, Bernhard Sick, Konrad Doll
mathjax: true
---

* content
{:toc}

##### Abstract
In this article, we present a novel approach to detect starting motions of cyclists in real world traffic scenarios based on Motion History Images (MHIs). The method uses a deep Convolutional Neural Network (CNN) with a residual network architecture (ResNet), which is commonly used in image classification and detection tasks. By combining MHIs with a ResNet classifier and performing a frame by frame classification of the MHIs, we are able to detect starting motions in image sequences. The detection is performed using a wide angle stereo camera system at an urban intersection. We compare our algorithm to an existing method to detect movement transitions of pedestrians that uses MHIs in combination with a Histograms of Oriented Gradients (HOG) like descriptor and a Support Vector Machine (SVM), which we adapted to cyclists. To train and evaluate the methods a dataset containing MHIs of 394 cyclist starting motions was created. The results show that both methods can be used to detect starting motions of cyclists. Using the SVM approach, we were able to safely detect starting motions 0.506 s on average after the bicycle starts moving with an F1-score of 97.7%. The ResNet approach achieved an F1-score of 100% at an average detection time of 0.144 s. The ResNet approach outperformed the SVM approach in both robustness against false positive detections and detection time.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于运动历史图像（MHI）检测真实世界交通场景中骑车人开始运动的新方法。该方法使用具有残余网络结构（ResNet）的深度卷积神经网络（CNN），其通常用于图像分类和检测任务。通过将MHI与ResNet分类器相结合，并对MHI进行逐帧分类，我们能够检测图像序列中的开始运动。在城市交叉路口使用广角立体摄像机系统进行检测。我们将我们的算法与现有的一种方法进行比较，以检测使用MHI的行人的运动转换，并结合面向方向梯度的直方图（HOG）（如描述符）和支持向量机（SVM），我们将其改编为骑车人。为了训练和评估方法，创建了包含394个骑车人开始动作的MHI的数据集。结果表明这两种方法都可以用来检测骑车人的起跑动作。使用SVM方法，在自行车开始移动之后，我们能够安全地检测到0.506秒的起始动作，F1得分为97.7％。 ResNet方法在平均检测时间为0.144秒时达到100％的F1分数。 ResNet方法在针对误报检测和检测时间的鲁棒性方面优于支持向量机方法。

##### URL
[http://arxiv.org/abs/1803.02242](http://arxiv.org/abs/1803.02242)

##### PDF
[http://arxiv.org/pdf/1803.02242](http://arxiv.org/pdf/1803.02242)

