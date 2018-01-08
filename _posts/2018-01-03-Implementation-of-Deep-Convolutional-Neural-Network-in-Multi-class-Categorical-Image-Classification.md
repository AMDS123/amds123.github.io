---
layout: post
title: "Implementation of Deep Convolutional Neural Network in Multi-class Categorical Image Classification"
date: 2018-01-03 15:29:44
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Optimization Classification Gradient_Descent
author: Pushparaja Murugan
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks has been implemented in many complex machine learning takes such as image classification, object identification, autonomous vehicle and robotic vision tasks. However, ConvNet architecture efficiency and accuracy depend on a large number of fac- tors. Also, the complex architecture requires a significant amount of data to train and involves with a large number of hyperparameters that increases the computational expenses and difficul- ties. Hence, it is necessary to address the limitations and techniques to overcome the barriers to ensure that the architecture performs well in complex visual tasks. This article is intended to develop an efficient ConvNet architecture for multi-class image categorical classification applica- tion. In the development of the architecture, large pool of grey scale images are taken as input information images and split into training and test datasets. The numerously available technique is implemented to reduce the overfitting and poor generalization of the network. The hyperpa- rameters of determined by Bayesian Optimization with Gaussian Process prior algorithm. ReLu non-linear activation function is implemented after the convolutional layers. Max pooling op- eration is carried out to downsampling the data points in pooling layers. Cross-entropy loss function is used to measure the performance of the architecture where the softmax is used in the classification layer. Mini-batch gradient descent with Adam optimizer algorithm is used for backpropagation. Developed architecture is validated with confusion matrix and classification report.

##### Abstract (translated by Google)
卷积神经网络已经应用于许多复杂的机器学习过程中，如图像分类，目标识别，自主车辆和机器人视觉任务等。然而，ConvNet架构的效率和精度取决于大量的因素。另外，复杂的体系结构需要大量的数据来训练和涉及大量的超参数，这会增加计算开销和难度。因此，有必要解决克服障碍的限制和技巧，以确保架构在复杂的视觉任务中表现良好。本文旨在为多类图像分类分类应用开发高效的ConvNet体系结构。在体系结构的发展中，将大量的灰度图像作为输入信息图像，并分解为训练和测试数据集。实施众多可用的技术来减少网络的过度配合和较差泛化。用高斯过程优先算法的贝叶斯优化确定的参数。 ReLu非线性激活函数是在卷积层之后实现的。执行最大池操作以对池层中的数据点进行降采样。交叉熵损失函数用于衡量softmax用于分类层的体系结构的性能。使用Adam优化器算法的小批量梯度下降用于反向传播。开发的体系结构通过混淆矩阵和分类报告进行验证。

##### URL
[http://arxiv.org/abs/1801.01397](http://arxiv.org/abs/1801.01397)

##### PDF
[http://arxiv.org/pdf/1801.01397](http://arxiv.org/pdf/1801.01397)

