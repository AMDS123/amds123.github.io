---
layout: post
title: "Cultural Event Recognition with Visual ConvNets and Temporal Models"
date: 2015-04-24 17:00:44
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction Recognition
author: Amaia Salvador, Matthias Zeppelzauer, Daniel Manchon-Vizuete, Andrea Calafell, Xavier Giro-i-Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents our contribution to the ChaLearn Challenge 2015 on Cultural Event Classification. The challenge in this task is to automatically classify images from 50 different cultural events. Our solution is based on the combination of visual features extracted from convolutional neural networks with temporal information using a hierarchical classifier scheme. We extract visual features from the last three fully connected layers of both CaffeNet (pretrained with ImageNet) and our fine tuned version for the ChaLearn challenge. We propose a late fusion strategy that trains a separate low-level SVM on each of the extracted neural codes. The class predictions of the low-level SVMs form the input to a higher level SVM, which gives the final event scores. We achieve our best result by adding a temporal refinement step into our classification scheme, which is applied directly to the output of each low-level SVM. Our approach penalizes high classification scores based on visual features when their time stamp does not match well an event-specific temporal distribution learned from the training and validation data. Our system achieved the second best result in the ChaLearn Challenge 2015 on Cultural Event Classification with a mean average precision of 0.767 on the test set.

##### Abstract (translated by Google)
本文介绍了我们对2015年文化事件分类挑战赛的贡献。这个任务的挑战是自动分类来自50个不同文化事件的图像。我们的解决方案基于从卷积神经网络提取的视觉特征与使用分层分类器方案的时间信息的组合。我们从CaffeNet的最后三个完全连接的层（用ImageNet预训练）和ChaLearn挑战的微调版本中提取视觉特征。我们提出了一个后期融合策略，在每个提取的神经代码上训练一个单独的低层SVM。低级别SVM的类别预测形成对较高级别SVM的输入，其给出最终事件分数。我们通过在我们的分类方案中增加一个时间细化步骤来实现我们的最佳结果，该分类方案直接应用于每个低级别SVM的输出。当他们的时间戳与从训练和验证数据中学到的特定于事件的时间分布不匹配时，我们的方法基于视觉特征惩罚高分类分数。我们的系统在2015年文化事件分类挑战赛中取得第二好成绩，测试集的平均精度为0.767。

##### URL
[https://arxiv.org/abs/1504.06567](https://arxiv.org/abs/1504.06567)

##### PDF
[https://arxiv.org/pdf/1504.06567](https://arxiv.org/pdf/1504.06567)

