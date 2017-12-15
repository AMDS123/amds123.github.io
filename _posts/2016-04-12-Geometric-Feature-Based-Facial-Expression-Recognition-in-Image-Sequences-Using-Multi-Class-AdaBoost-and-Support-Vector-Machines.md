---
layout: post
title: "Geometric Feature-Based Facial Expression Recognition in Image Sequences Using Multi-Class AdaBoost and Support Vector Machines"
date: 2016-04-12 03:00:13
categories: arXiv_CV
tags: arXiv_CV Tracking Recognition
author: Deepak Ghimire, Joonwhoan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Facial expressions are widely used in the behavioral interpretation of emotions, cognitive science, and social interactions. In this paper, we present a novel method for fully automatic facial expression recognition in facial image sequences. As the facial expression evolves over time facial landmarks are automatically tracked in consecutive video frames, using displacements based on elastic bunch graph matching displacement estimation. Feature vectors from individual landmarks, as well as pairs of landmarks tracking results are extracted, and normalized, with respect to the first frame in the sequence. The prototypical expression sequence for each class of facial expression is formed, by taking the median of the landmark tracking results from the training facial expression sequences. Multi-class AdaBoost with dynamic time warping similarity distance between the feature vector of input facial expression and prototypical facial expression, is used as a weak classifier to select the subset of discriminative feature vectors. Finally, two methods for facial expression recognition are presented, either by using multi-class AdaBoost with dynamic time warping, or by using support vector machine on the boosted feature vectors. The results on the Cohn-Kanade (CK+) facial expression database show a recognition accuracy of 95.17% and 97.35% using multi-class AdaBoost and support vector machines, respectively.

##### Abstract (translated by Google)
面部表情被广泛用于情绪，认知科学和社会交往的行为解释。在本文中，我们提出了一种新的面部图像序列中的全自动表情识别方法。随着时间的推移面部表情随着时间的推移而被连续的视频帧自动跟踪，使用基于弹性束图匹配位移估计的位移。提取来自各个地标的特征矢量以及成对的地标跟踪结果，并对该序列中的第一帧进行归一化。通过从训练面部表情序列中取得标志物追踪结果的中值，形成每类面部表情的原型表情序列。将输入面部表情特征向量与原型面部表情之间的动态时间规整相似距离的多类AdaBoost作为弱分类器来选择判别特征向量的子集。最后，提出了两种面向表情识别的方法，即采用动态时间弯曲的多类AdaBoost，或者利用支持向量机对提升特征向量进行识别。 Cohn-Kanade（CK +）人脸表情数据库的结果表明，使用多类AdaBoost和支持向量机，识别率分别为95.17％和97.35％。

##### URL
[https://arxiv.org/abs/1604.03225](https://arxiv.org/abs/1604.03225)

##### PDF
[https://arxiv.org/pdf/1604.03225](https://arxiv.org/pdf/1604.03225)

