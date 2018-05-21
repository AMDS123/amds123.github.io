---
layout: post
title: "Deep Convolutional Decision Jungle for Image Classification"
date: 2018-05-18 12:53:33
categories: arXiv_CV
tags: arXiv_CV Sparse Face CNN Image_Classification Optimization Classification Gradient_Descent
author: Seungryul Baek, Kwang In Kim, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method called deep convolutional decision jungle (CDJ) and its learning algorithm for image classification. The CDJ maintains the structure of standard convolutional neural networks (CNNs), i.e. multiple layers of multiple response maps fully connected. Each response map-or node-in both the convolutional and fully-connected layers selectively respond to class labels s.t. each data sample travels via a specific soft route of those activated nodes. The proposed method CDJ automatically learns features, whereas decision forests and jungles require pre-defined feature sets. Compared to CNNs, the method embeds the benefits of using data-dependent discriminative functions, which better handles multi-modal/heterogeneous data; further,the method offers more diverse sparse network responses, which in turn can be used for cost-effective learning/classification. The network is learnt by combining conventional softmax and proposed entropy losses in each layer. The entropy loss,as used in decision tree growing, measures the purity of data activation according to the class label distribution. The back-propagation rule for the proposed loss function is derived from stochastic gradient descent (SGD) optimization of CNNs. We show that our proposed method outperforms state-of-the-art methods on three public image classification benchmarks and one face verification dataset. We also demonstrate the use of auxiliary data labels, when available, which helps our method to learn more discriminative routing and representations and leads to improved classification.

##### Abstract (translated by Google)
我们提出了一种称为深度卷积决策丛林（CDJ）的新方法及其用于图像分类的学习算法。 CDJ维护标准卷积神经网络（CNN）的结构，即完全连接的多层多重响应图。卷积层和完全连接层中的每个响应图或节点有选择地响应类标签s.t.每个数据样本通过这些激活节点的特定软路由传播。所提出的方法CDJ自动学习特征，而决策森林和丛林需要预先定义的特征集。与CNN相比，该方法嵌入了使用依赖数据的判别函数的好处，它更好地处理多模式/异构数据;此外，该方法提供了更多不同的稀疏网络响应，这反过来又可用于具有成本效益的学习/分类。通过结合传统的softmax和每层中提出的熵损失来学习网络。在决策树增长中使用的熵损根据类别标签分布来度量数据激活的纯度。所提出的损失函数的反向传播规则来源于CNN的随机梯度下降（SGD）优化。我们表明，我们提出的方法优于三个公共图像分类基准和一个人脸验证数据集的最先进的方法。我们还演示了在可用时使用辅助数据标签，这有助于我们的方法学习更多区分性的路由和表示，并导致改进的分类。

##### URL
[http://arxiv.org/abs/1706.02003](http://arxiv.org/abs/1706.02003)

##### PDF
[http://arxiv.org/pdf/1706.02003](http://arxiv.org/pdf/1706.02003)

