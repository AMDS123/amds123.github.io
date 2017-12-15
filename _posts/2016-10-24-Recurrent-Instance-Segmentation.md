---
layout: post
title: "Recurrent Instance Segmentation"
date: 2016-10-24 23:57:19
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Bernardino Romera-Paredes, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Instance segmentation is the problem of detecting and delineating each distinct object of interest appearing in an image. Current instance segmentation approaches consist of ensembles of modules that are trained independently of each other, thus missing opportunities for joint learning. Here we propose a new instance segmentation paradigm consisting in an end-to-end method that learns how to segment instances sequentially. The model is based on a recurrent neural network that sequentially finds objects and their segmentations one at a time. This net is provided with a spatial memory that keeps track of what pixels have been explained and allows occlusion handling. In order to train the model we designed a principled loss function that accurately represents the properties of the instance segmentation problem. In the experiments carried out, we found that our method outperforms recent approaches on multiple person segmentation, and all state of the art approaches on the Plant Phenotyping dataset for leaf counting.

##### Abstract (translated by Google)
实例分割是检测和描绘出现在图像中的每个不同的感兴趣对象的问题。当前的实例分割方法由彼此独立训练的模块集合组成，因此失去联合学习的机会。在这里我们提出了一个新的实例分割范例，它包含一个端到端的方法，该方法学习如何顺序地分割实例。该模型基于循环神经网络，该网络一次一个地依次查找对象及其分段。这个网络提供了一个空间记忆，记录了什么像素被解释，并允许遮挡处理。为了训练模型，我们设计了一个准确表示实例分割问题属性的原则性损失函数。在所进行的实验中，我们发现，我们的方法胜过最近的多人分割方法，并且所有的现有技术方法都在植物叶表型数据集上进行。

##### URL
[https://arxiv.org/abs/1511.08250](https://arxiv.org/abs/1511.08250)

##### PDF
[https://arxiv.org/pdf/1511.08250](https://arxiv.org/pdf/1511.08250)

