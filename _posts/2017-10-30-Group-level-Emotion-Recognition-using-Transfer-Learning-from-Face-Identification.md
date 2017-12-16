---
layout: post
title: "Group-level Emotion Recognition using Transfer Learning from Face Identification"
date: 2017-10-30 19:33:12
categories: arXiv_CV
tags: arXiv_CV Face CNN Transfer_Learning Recognition
author: Alexandr G. Rassadin, Alexey S. Gruzdev, Andrey V. Savchenko
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe our algorithmic approach, which was used for submissions in the fifth Emotion Recognition in the Wild (EmotiW 2017) group-level emotion recognition sub-challenge. We extracted feature vectors of detected faces using the Convolutional Neural Network trained for face identification task, rather than traditional pre-training on emotion recognition problems. In the final pipeline an ensemble of Random Forest classifiers was learned to predict emotion score using available training set. In case when the faces have not been detected, one member of our ensemble extracts features from the whole image. During our experimental study, the proposed approach showed the lowest error rate when compared to other explored techniques. In particular, we achieved 75.4% accuracy on the validation data, which is 20% higher than the handcrafted feature-based baseline. The source code using Keras framework is publicly available.

##### Abstract (translated by Google)
在本文中，我们描述了我们的算法方法，该方法被用于在野外（EmotiW 2017）团体级情绪识别子挑战中的第五次情绪识别。我们使用卷积神经网络训练人脸识别任务，而不是传统的情绪识别问题的预训练提取检测到的人脸的特征向量。在最后的管道中，学习随机森林分类器的集合，以使用可用的训练集来预测情感分数。在脸部未被检测到的情况下，我们的一个成员从整个图像中提取特征。在我们的实验研究中，与其他探索技术相比，所提出的方法显示出最低的错误率。特别是，我们在验证数据上的准确率达到了75.4％，比基于手工功能的基线高出20％。使用Keras框架的源代码是公开的。

##### URL
[https://arxiv.org/abs/1709.01688](https://arxiv.org/abs/1709.01688)

##### PDF
[https://arxiv.org/pdf/1709.01688](https://arxiv.org/pdf/1709.01688)

