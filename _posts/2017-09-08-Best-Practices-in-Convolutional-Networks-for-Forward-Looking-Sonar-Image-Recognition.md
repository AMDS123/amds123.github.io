---
layout: post
title: "Best Practices in Convolutional Networks for Forward-Looking Sonar Image Recognition"
date: 2017-09-08 09:14:25
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification Relation Recognition
author: Matias Valdenegro-Toro
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) have revolutionized perception for color images, and their application to sonar images has also obtained good results. But in general CNNs are difficult to train without a large dataset, need manual tuning of a considerable number of hyperparameters, and require many careful decisions by a designer. In this work, we evaluate three common decisions that need to be made by a CNN designer, namely the performance of transfer learning, the effect of object/image size and the relation between training set size. We evaluate three CNN models, namely one based on LeNet, and two based on the Fire module from SqueezeNet. Our findings are: Transfer learning with an SVM works very well, even when the train and transfer sets have no classes in common, and high classification performance can be obtained even when the target dataset is small. The ADAM optimizer combined with Batch Normalization can make a high accuracy CNN classifier, even with small image sizes (16 pixels). At least 50 samples per class are required to obtain $90\%$ test accuracy, and using Dropout with a small dataset helps improve performance, but Batch Normalization is better when a large dataset is available.

##### Abstract (translated by Google)
卷积神经网络（CNN）使彩色图像的感知发生了革命性的变化，其在声纳图像上的应用也取得了良好的效果。但是一般而言，如果没有大数据集，CNN就很难训练，需要手动调整大量的超参数，并且需要设计师做出许多谨慎的决定。在这项工作中，我们评估了CNN设计者需要做出的三个共同决定，即转移学习的表现，对象/图像大小的影响以及训练集大小之间的关系。我们评估了三个CNN模型，一个基于LeNet，另外两个基于SqueezeNet的Fire模块。我们的发现是：即使在训练集和传输集没有共同类的情况下，即使在目标数据集小的情况下也可以获得高分类性能，但是使用SVM的转移学习效果很好。 ADAM优化器与批量标准化相结合，即使在图像尺寸较小（16像素）的情况下，也可以生成高精度的CNN分类器。每个班级至少需要50个样本才能获得$ 90 \％$的测试准确度，并且使用Dropout和一个小数据集有助于提高性能，但是当大型数据集可用时，Batch Normalization会更好。

##### URL
[https://arxiv.org/abs/1709.02601](https://arxiv.org/abs/1709.02601)

##### PDF
[https://arxiv.org/pdf/1709.02601](https://arxiv.org/pdf/1709.02601)

