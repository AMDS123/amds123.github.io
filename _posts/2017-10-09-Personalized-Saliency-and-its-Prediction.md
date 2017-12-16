---
layout: post
title: "Personalized Saliency and its Prediction"
date: 2017-10-09 09:43:48
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Prediction Detection Relation
author: Yanyu Xu, Junru Wu, Nianyi Li, Shenghua Gao, Jingyi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Almost all existing visual saliency models focus on predicting a universal saliency map across all observers. Yet psychology studies suggest that visual attention of different observers can vary a lot under some specific circumstances, especially when they view scenes with multiple salient objects. However, few work explores this visual attention difference probably because of lacking a proper dataset, as well as complex correlation between visual attention, personal preferences, and image contents. In this paper, we set out to study this heterogenous visual attention pattern between different observers and build the first dataset for personalized saliency detection. Further, we propose to decompose a personalized saliency map (referred to as PSM) into a universal saliency map (referred to as USM) which can be predicted by any existing saliency detection models and a discrepancy between them. Then personalized saliency detection is casted as the task of discrepancy estimation between PSM and USM. To tackle this task we propose two solutions: i) The discrepancy estimation for different observers are casted as different but related tasks. Then we feed the image and its USM into a multi-task convolutional neural network framework to estimate the discrepancy between PSM and USM for each observer; ii) As the discrepancy is related to both image contents and the observers' person-specific information, we feed the image and its associated USM into a convolutional neural network with person-specific information encoded filters to estimate the discrepancy. Extensive experimental results demonstrate the effectiveness of our models for PSM prediction as well their generalization capability for unseen observers.

##### Abstract (translated by Google)
几乎所有现有的视觉显着性模型都着眼于预测所有观察者的普遍显着性图。然而心理学研究表明，不同观察者的视觉注意力在一些特定情况下可能会有很大差异，特别是当他们观察具有多个显着物体的场景时。然而，由于缺乏恰当的数据集，以及视觉注意力，个人喜好和图像内容之间复杂的相关性，很少有研究探讨这种视觉注意力差异。在本文中，我们着手研究不同观察者之间的异质视觉注意模式，并建立个性化显着性检测的第一个数据集。此外，我们建议将个性化显着图（称为PSM）分解成通用显着图（称为USM），其可以通过任何现有的显着性检测模型和它们之间的差异来预测。然后将个性化显着性检测作为PSM和USM差异估计的任务。为了解决这个问题，我们提出了两个解决方案：（1）不同观察者的差异估计是作为不同的但相关的任务。然后，我们将图像及其USM送入多任务卷积神经网络框架，以估计每个观察者的PSM和USM之间的差异; ii）由于差异与图像内容和观察者的特定个人信息有关，我们将图像及其相关的USM馈送到具有个人特定信息编码过滤器的卷积神经网络中以估计差异。广泛的实验结果证明了我们的PSM预测模型的有效性以及它们对于看不见的观察者的泛化能力。

##### URL
[https://arxiv.org/abs/1710.03011](https://arxiv.org/abs/1710.03011)

##### PDF
[https://arxiv.org/pdf/1710.03011](https://arxiv.org/pdf/1710.03011)

