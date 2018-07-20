---
layout: post
title: "Bio-Measurements Estimation and Support in Knee Recovery through Machine Learning"
date: 2018-07-19 16:24:22
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Deep_Learning Prediction
author: João Bernardino (1), Luís Filipe Teixeira (1 and 2), Hugo Sereno Ferreira (1 and 2) ((1) DEI - Faculty of Engineering - University of Porto, (2) INESC TEC)
mathjax: true
---

* content
{:toc}

##### Abstract
Knee injuries are frequent, varied and often require the patient to undergo intensive rehabilitation for several months. Treatment protocols usually contemplate some recurrent measurements in order to assess progress, such as goniometry. The need for specific equipment or the complexity and duration of these tasks cause them to often be neglected. A novel deep learning based solution is presented, supported by the generation of a synthetic image dataset. A 3D human-body model was used for this purpose, simulating a recovering patient. For each image, the coordinates of three key points were registered: the centers of the thigh, the knee and the lower leg. These values are sufficient to estimate the flexion angle. Convolutional neural networks were then trained for predicting these six coordinates. Transfer learning was used with the VGG16 and InceptionV3 models pre-trained on the ImageNet dataset, being an additional custom model trained from scratch. All models were tested with different combinations of data augmentation techniques applied on the training sets. InceptionV3 achieved the best overall results, producing considerably good predictions even on real unedited pictures.

##### Abstract (translated by Google)
膝关节损伤是经常发生的，多种多样，并且通常需要患者进行数月的强化康复。治疗方案通常考虑一些重复测量以评估进展，例如测角测量。对特定设备的需求或这些任务的复杂性和持续时间使它们经常被忽视。提出了一种新的基于深度学习的解决方案，该方案由合成图像数据集的生成支持。为此目的使用3D人体模型，模拟恢复的患者。对于每个图像，记录了三个关键点的坐标：大腿，膝盖和小腿的中心。这些值足以估计屈曲角度。然后训练卷积神经网络以预测这六个坐标。转移学习与在ImageNet数据集上预先训练的VGG16和InceptionV3模型一起使用，是从头开始训练的另一个定制模型。所有模型都使用应用于训练集的不同数据增强技术组合进行测试。 InceptionV3取得了最佳的整体效果，即使在真实的未经编辑的图片上也能产生相当好的预测效果。

##### URL
[https://arxiv.org/abs/1807.07521](https://arxiv.org/abs/1807.07521)

##### PDF
[https://arxiv.org/pdf/1807.07521](https://arxiv.org/pdf/1807.07521)

