---
layout: post
title: "NO Need to Worry about Adversarial Examples in Object Detection in Autonomous Vehicles"
date: 2017-07-12 00:09:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Jiajun Lu, Hussein Sibai, Evan Fabry, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
It has been shown that most machine learning algorithms are susceptible to adversarial perturbations. Slightly perturbing an image in a carefully chosen direction in the image space may cause a trained neural network model to misclassify it. Recently, it was shown that physical adversarial examples exist: printing perturbed images then taking pictures of them would still result in misclassification. This raises security and safety concerns. However, these experiments ignore a crucial property of physical objects: the camera can view objects from different distances and at different angles. In this paper, we show experiments that suggest that current constructions of physical adversarial examples do not disrupt object detection from a moving platform. Instead, a trained neural network classifies most of the pictures taken from different distances and angles of a perturbed image correctly. We believe this is because the adversarial property of the perturbation is sensitive to the scale at which the perturbed picture is viewed, so (for example) an autonomous car will misclassify a stop sign only from a small range of distances. Our work raises an important question: can one construct examples that are adversarial for many or most viewing conditions? If so, the construction should offer very significant insights into the internal representation of patterns by deep networks. If not, there is a good prospect that adversarial examples can be reduced to a curiosity with little practical impact.

##### Abstract (translated by Google)
已经表明，大多数机器学习算法易受对抗性干扰的影响。在图像空间中仔细选择的方向稍微扰动图像可能会导致训练的神经网络模型对其进行错误分类。最近的研究表明，存在一些对抗的例子：打印图像然后拍摄它们仍然会导致错误的分类。这提出了安全和安全问题。然而，这些实验忽略了物理物体的一个重要属性：相机可以从不同的距离和不同的角度观看物体。在本文中，我们展示的实验表明，当前的物理对抗示例的构造不会干扰移动平台上的对象检测。相反，经过训练的神经网络将大部分正确地从不同距离和角度拍摄的照片分类。我们认为这是因为扰动的对抗性对于观看扰动图像的尺度是敏感的，所以（例如）自动汽车将仅从小范围的距离错误地分类停车标志。我们的工作提出了一个重要的问题：能否构建对许多或大多数观看条件是敌对的例子？如果是这样，这个建筑应该通过深层网络对模式的内部表示提供非常重要的见解。如果不是这样，有一个好的前景，对抗的例子可以减少一个好奇心，几乎没有实际的影响。

##### URL
[https://arxiv.org/abs/1707.03501](https://arxiv.org/abs/1707.03501)

##### PDF
[https://arxiv.org/pdf/1707.03501](https://arxiv.org/pdf/1707.03501)

