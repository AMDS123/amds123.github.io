---
layout: post
title: "Visual Concepts and Compositional Voting"
date: 2017-11-13 07:29:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jianyu Wang, Zhishuai Zhang, Cihang Xie, Yuyin Zhou, Vittal Premachandran, Jun Zhu, Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
It is very attractive to formulate vision in terms of pattern theory \cite{Mumford2010pattern}, where patterns are defined hierarchically by compositions of elementary building blocks. But applying pattern theory to real world images is currently less successful than discriminative methods such as deep networks. Deep networks, however, are black-boxes which are hard to interpret and can easily be fooled by adding occluding objects. It is natural to wonder whether by better understanding deep networks we can extract building blocks which can be used to develop pattern theoretic models. This motivates us to study the internal representations of a deep network using vehicle images from the PASCAL3D+ dataset. We use clustering algorithms to study the population activities of the features and extract a set of visual concepts which we show are visually tight and correspond to semantic parts of vehicles. To analyze this we annotate these vehicles by their semantic parts to create a new dataset, VehicleSemanticParts, and evaluate visual concepts as unsupervised part detectors. We show that visual concepts perform fairly well but are outperformed by supervised discriminative methods such as Support Vector Machines (SVM). We next give a more detailed analysis of visual concepts and how they relate to semantic parts. Following this, we use the visual concepts as building blocks for a simple pattern theoretical model, which we call compositional voting. In this model several visual concepts combine to detect semantic parts. We show that this approach is significantly better than discriminative methods like SVM and deep networks trained specifically for semantic part detection. Finally, we return to studying occlusion by creating an annotated dataset with occlusion, called VehicleOcclusion, and show that compositional voting outperforms even deep networks when the amount of occlusion becomes large.

##### Abstract (translated by Google)
用模式理论来表达愿景是非常有吸引力的，其中模式是由基本构件块的组合来定义的。但是将模式理论应用于现实世界的图像目前不如深层网络这样的区分方法成功。但是深度网络是黑盒子，很难解释，很容易被添加遮挡物体所迷惑。很自然地想知道，通过深入了解深层网络，我们能够提取可用于开发模式理论模型的构建块。这激励我们使用来自PASCAL3D +数据集的车辆图像来研究深度网络的内部表示。我们使用聚类算法来研究特征的人口活动，并提取一组视觉概念，这些概念在视觉上是紧密的，并且与车辆的语义部分相对应。为了分析这一点，我们用这些车辆的语义部分来标注这些车辆，以创建一个新的数据集VehicleSemanticParts，并将视觉概念评估为无监督的部分检测器。我们表明，视觉概念表现相当好，但是通过支持向量机（SVM）等有监督的判别方法表现出色。接下来，我们将更详细地分析视觉概念以及它们与语义部分之间的关​​系。接下来，我们将视觉概念作为一个简单的模式理论模型的基石，我们称之为组合投票。在这个模型中，几个视觉概念结合在一起来检测语义部分。我们表明，这种方法明显好于歧视性的方法，如SVM和专门为语义部分检测而训练的深度网络。最后，我们通过创建一个带有遮挡的注释数据集（称为VehicleOcclusion）来重新研究遮挡，并且显示当遮挡量变大时，构图投票甚至胜过深度网络。

##### URL
[https://arxiv.org/abs/1711.04451](https://arxiv.org/abs/1711.04451)

##### PDF
[https://arxiv.org/pdf/1711.04451](https://arxiv.org/pdf/1711.04451)

