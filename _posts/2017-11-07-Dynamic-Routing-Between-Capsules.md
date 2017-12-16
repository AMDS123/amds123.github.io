---
layout: post
title: "Dynamic Routing Between Capsules"
date: 2017-11-07 19:26:38
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Sara Sabour, Nicholas Frosst, Geoffrey E Hinton
mathjax: true
---

* content
{:toc}

##### Abstract
A capsule is a group of neurons whose activity vector represents the instantiation parameters of a specific type of entity such as an object or an object part. We use the length of the activity vector to represent the probability that the entity exists and its orientation to represent the instantiation parameters. Active capsules at one level make predictions, via transformation matrices, for the instantiation parameters of higher-level capsules. When multiple predictions agree, a higher level capsule becomes active. We show that a discrimininatively trained, multi-layer capsule system achieves state-of-the-art performance on MNIST and is considerably better than a convolutional net at recognizing highly overlapping digits. To achieve these results we use an iterative routing-by-agreement mechanism: A lower-level capsule prefers to send its output to higher level capsules whose activity vectors have a big scalar product with the prediction coming from the lower-level capsule.

##### Abstract (translated by Google)
胶囊是一组神经元，其活动向量表示特定类型实体（例如对象或对象部分）的实例化参数。我们使用活动向量的长度来表示实体存在的概率及其表示实例化参数的方向。在一个级别上的活性胶囊通过变换矩阵来预测高级胶囊的实例化参数。当多个预测一致时，更高级别的胶囊变得活跃。我们表明，一个有识别的训练，多层胶囊系统达到MNIST的最先进的性能，并且比识别高度重叠的数字的卷积网好得多。为了达到这些结果，我们使用了一种迭代路由协议机制：一个较低级别的胶囊倾向于将其输出发送到较高级别的胶囊，其活动向量具有较高的标量乘积，并且来自较低级别胶囊的预测。

##### URL
[https://arxiv.org/abs/1710.09829](https://arxiv.org/abs/1710.09829)

##### PDF
[https://arxiv.org/pdf/1710.09829](https://arxiv.org/pdf/1710.09829)

