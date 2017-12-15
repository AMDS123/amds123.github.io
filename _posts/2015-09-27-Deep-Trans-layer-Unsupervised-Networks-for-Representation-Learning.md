---
layout: post
title: "Deep Trans-layer Unsupervised Networks for Representation Learning"
date: 2015-09-27 00:46:08
categories: arXiv_CV
tags: arXiv_CV Face Represenation_Learning Classification Deep_Learning Recognition
author: Wentao Zhu, Jun Miao, Laiyun Qing, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Learning features from massive unlabelled data is a vast prevalent topic for high-level tasks in many machine learning applications. The recent great improvements on benchmark data sets achieved by increasingly complex unsupervised learning methods and deep learning models with lots of parameters usually requires many tedious tricks and much expertise to tune. However, filters learned by these complex architectures are quite similar to standard hand-crafted features visually. In this paper, unsupervised learning methods, such as PCA or auto-encoder, are employed as the building block to learn filter banks at each layer. The lower layer responses are transferred to the last layer (trans-layer) to form a more complete representation retaining more information. In addition, some beneficial methods such as local contrast normalization and whitening are added to the proposed deep trans-layer networks to further boost performance. The trans-layer representations are followed by block histograms with binary encoder schema to learn translation and rotation invariant representations, which are utilized to do high-level tasks such as recognition and classification. Compared to traditional deep learning methods, the implemented feature learning method has much less parameters and is validated in several typical experiments, such as digit recognition on MNIST and MNIST variations, object recognition on Caltech 101 dataset and face verification on LFW dataset. The deep trans-layer unsupervised learning achieves 99.45% accuracy on MNIST dataset, 67.11% accuracy on 15 samples per class and 75.98% accuracy on 30 samples per class on Caltech 101 dataset, 87.10% on LFW dataset.

##### Abstract (translated by Google)
从大量未标记的数据中学习功能是许多机器学习应用程序中高级任务的广泛流行主题。最近通过越来越复杂的无监督学习方法和具有大量参数的深度学习模型实现的基准数据集的重大改进通常需要许多繁琐的技巧和许多专业知识来调整。但是，由这些复杂架构学习的过滤器与标准的手工制作功能在视觉上非常相似。本文采用无监督学习方法（如PCA或自编码器）作为构建模块来学习各层的滤波器组。下层响应被转移到最后一层（跨层），以形成保留更多信息的更完整的表示。另外，在提出的深层跨层网络中增加了一些有益的方法，如局部对比度归一化和白化，以进一步提升性能。在跨层表示之后是具有二进制编码器模式的块直方图，以学习用于执行诸如识别和分类的高级任务的平移和旋转不变表示。与传统的深度学习方法相比，实现的特征学习方法参数少得多，在MNIST和MNIST变换的数字识别，Caltech 101数据集的对象识别和LFW数据集的人脸验证等几个典型实验中得到验证。深层跨层次无监督学习在MNIST数据集上的准确率达到99.45％，每班15个样本的准确率为67.11％，加州理工学院101数据集每班30个样本的准确率为75.98％，LFW数据集的准确率为87.10％。

##### URL
[https://arxiv.org/abs/1509.08038](https://arxiv.org/abs/1509.08038)

##### PDF
[https://arxiv.org/pdf/1509.08038](https://arxiv.org/pdf/1509.08038)

