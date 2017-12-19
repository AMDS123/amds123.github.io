---
layout: post
title: "Multi-view Face Detection Using Deep Convolutional Neural Networks"
date: 2015-04-20 20:18:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Face CNN Deep_Learning Detection Face_Detection Relation
author: Sachin Sudhakar Farfade, Mohammad Saberian, Li-Jia Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we consider the problem of multi-view face detection. While there has been significant research on this problem, current state-of-the-art approaches for this task require annotation of facial landmarks, e.g. TSM [25], or annotation of face poses [28, 22]. They also require training dozens of models to fully capture faces in all orientations, e.g. 22 models in HeadHunter method [22]. In this paper we propose Deep Dense Face Detector (DDFD), a method that does not require pose/landmark annotation and is able to detect faces in a wide range of orientations using a single model based on deep convolutional neural networks. The proposed method has minimal complexity; unlike other recent deep learning object detection methods [9], it does not require additional components such as segmentation, bounding-box regression, or SVM classifiers. Furthermore, we analyzed scores of the proposed face detector for faces in different orientations and found that 1) the proposed method is able to detect faces from different angles and can handle occlusion to some extent, 2) there seems to be a correlation between dis- tribution of positive examples in the training set and scores of the proposed face detector. The latter suggests that the proposed methods performance can be further improved by using better sampling strategies and more sophisticated data augmentation techniques. Evaluations on popular face detection benchmark datasets show that our single-model face detector algorithm has similar or better performance compared to the previous methods, which are more complex and require annotations of either different poses or facial landmarks.

##### Abstract (translated by Google)
在本文中，我们考虑多视角人脸检测的问题。虽然已经对这个问题进行了重要的研究，但是目前用于该任务的现有技术方法需要注释面部标志，例如， TSM [25]或脸部姿势的注释[28,22]。他们还需要训练几十个模型，以全方位地捕捉人脸。在HeadHunter方法中有22个模型[22]。在本文中，我们提出了深密人脸检测器（DDFD），这种方法不需要姿态/地标注释，并且能够使用基于深度卷积神经网络的单个模型在各种方向上检测人脸。该方法具有最小的复杂度;不像其他最近的深度学习对象检测方法[9]，它不需要额外的组件，如分割，边界框回归或支持向量机分类器。此外，我们分析了所提出的人脸检测方法在不同方向上的得分，发现：1）该方法能够检测不同角度的人脸，并能在一定程度上处理人脸遮挡; 2）对所提出的人脸检测器的训练集和得分进行正面例证分析。后者表明，所提出的方法性能可以通过使用更好的采样策略和更复杂的数据增强技术进一步改善。对流行的人脸检测基准数据集的评估表明，与先前的方法相比，我们的单模型人脸检测器算法具有相似或更好的性能，所述方法更复杂并且要求注释不同的姿势或面部标志。

##### URL
[https://arxiv.org/abs/1502.02766](https://arxiv.org/abs/1502.02766)

##### PDF
[https://arxiv.org/pdf/1502.02766](https://arxiv.org/pdf/1502.02766)

