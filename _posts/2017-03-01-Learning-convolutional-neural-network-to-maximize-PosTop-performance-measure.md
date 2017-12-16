---
layout: post
title: "Learning convolutional neural network to maximize Pos@Top performance measure"
date: 2017-03-01 02:55:45
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Yanyan Geng, Ru-Ze Liang, Weizhi Li, Jingbin Wang, Gaoyuan Liang, Chenhao Xu, Jing-Yan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In the machine learning problems, the performance measure is used to evaluate the machine learning models. Recently, the number positive data points ranked at the top positions (Pos@Top) has been a popular performance measure in the machine learning community. In this paper, we propose to learn a convolutional neural network (CNN) model to maximize the Pos@Top performance measure. The CNN model is used to represent the multi-instance data point, and a classifier function is used to predict the label from the its CNN representation. We propose to minimize the loss function of Pos@Top over a training set to learn the filters of CNN and the classifier parameter. The classifier parameter vector is solved by the Lagrange multiplier method, and the filters are updated by the gradient descent method alternately in an iterative algorithm. Experiments over benchmark data sets show that the proposed method outperforms the state-of-the-art Pos@Top maximization methods.

##### Abstract (translated by Google)
在机器学习问题中，性能测量被用来评估机器学习模型。最近，在机器学习社区中排在最高位置（Pos @ Top）的数量正面数据点一直是一个流行的表现指标。在本文中，我们建议学习卷积神经网络（CNN）模型来最大化Pos @ Top性能度量。使用CNN模型来表示多实例数据点，并且使用分类器函数来从CNN表示中预测标签。我们建议最大限度地减少Pos @ Top在训练集上的损失函数来学习CNN的滤波器和分类器参数。采用拉格朗日乘子法求解分类器参数向量，迭代算法交替采用梯度下降法对滤波器进行更新。基准数据集上的实验表明，所提出的方法优于最先进的Pos @ Top最大化方法。

##### URL
[https://arxiv.org/abs/1609.08417](https://arxiv.org/abs/1609.08417)

##### PDF
[https://arxiv.org/pdf/1609.08417](https://arxiv.org/pdf/1609.08417)

