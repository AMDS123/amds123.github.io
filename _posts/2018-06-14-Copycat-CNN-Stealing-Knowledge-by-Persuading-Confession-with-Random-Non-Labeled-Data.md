---
layout: post
title: "Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data"
date: 2018-06-14 11:32:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge CNN Classification Prediction
author: Jacson Rodrigues Correia-Silva, Rodrigo F. Berriel, Claudine Badue, Alberto F. de Souza, Thiago Oliveira-Santos
mathjax: true
---

* content
{:toc}

##### Abstract
In the past few years, Convolutional Neural Networks (CNNs) have been achieving state-of-the-art performance on a variety of problems. Many companies employ resources and money to generate these models and provide them as an API, therefore it is in their best interest to protect them, i.e., to avoid that someone else copies them. Recent studies revealed that state-of-the-art CNNs are vulnerable to adversarial examples attacks, and this weakness indicates that CNNs do not need to operate in the problem domain (PD). Therefore, we hypothesize that they also do not need to be trained with examples of the PD in order to operate in it. 
 Given these facts, in this paper, we investigate if a target black-box CNN can be copied by persuading it to confess its knowledge through random non-labeled data. The copy is two-fold: i) the target network is queried with random data and its predictions are used to create a fake dataset with the knowledge of the network; and ii) a copycat network is trained with the fake dataset and should be able to achieve similar performance as the target network. 
 This hypothesis was evaluated locally in three problems (facial expression, object, and crosswalk classification) and against a cloud-based API. In the copy attacks, images from both non-problem domain and PD were used. All copycat networks achieved at least 93.7% of the performance of the original models with non-problem domain data, and at least 98.6% using additional data from the PD. Additionally, the copycat CNN successfully copied at least 97.3% of the performance of the Microsoft Azure Emotion API. Our results show that it is possible to create a copycat CNN by simply querying a target network as black-box with random non-labeled data.

##### Abstract (translated by Google)
在过去的几年中，卷积神经网络（CNN）一直在各种问题上取得了最先进的性能。许多公司聘请资源和资金来生成这些模型并将其作为API提供，因此保护它们是最有利的，即避免其他人复制它们。最近的研究表明，最先进的CNN很容易遭受敌对的例子攻击，而这种弱点表明CNN不需要在问题域（PD）中运行。因此，我们假设他们也不需要通过PD的例子进行培训以便在其中进行操作。
 鉴于这些事实，在本文中，我们调查目标黑盒CNN是否可以通过说服它通过随机无标签数据来承认它的知识而被复制。该副本有两层：i）目标网络用随机数据查询，其预测用于创建具有网络知识的假数据集;和ii）复制网络用假数据集进行训练，并且应该能够实现与目标网络相似的性能。
 这个假设在三个问题（面部表情，对象和人行横道分类）和基于云的API中进行了局部评估。在复制攻击中，使用了来自非问题域和PD的图像。所有模仿网络实现了至少93.7％的具有无问题域数据的原始模型的性能，并且至少有98.6％使用来自PD的额外数据。另外，模仿CNN的成功复制了至少97.3％的Microsoft Azure Emotion API性能。我们的结果表明，通过简单地将目标网络查询为带有随机未标记数据的黑盒子，可以创建一个模仿CNN。

##### URL
[http://arxiv.org/abs/1806.05476](http://arxiv.org/abs/1806.05476)

##### PDF
[http://arxiv.org/pdf/1806.05476](http://arxiv.org/pdf/1806.05476)

