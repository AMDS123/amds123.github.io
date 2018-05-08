---
layout: post
title: "A Hierarchical Matcher using Local Classifier Chains"
date: 2018-05-07 04:29:19
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Lingfeng Zhang, Ioannis A. Kakadiaris
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on improving the performance of current convolutional neural networks in visual recognition without changing the network architecture. A hierarchical matcher is proposed that builds chains of local binary neural networks after one global neural network over all the class labels, named as Local Classifier Chains based Convolutional Neural Network (LCC-CNN). The signature of each sample as two components: global component based on the global network; local component based on local binary networks. The local networks are built based on label pairs created by a similarity matrix and confusion matrix. During matching, each sample travels through one global network and a chain of local networks to obtain its final matching to avoid error propagation. The proposed matcher has been evaluated with image recognition, character recognition and face recognition datasets. The experimental results indicate that the proposed matcher achieves better performance when compared with methods using only a global deep network. Compared with the UR2D system, the accuracy is improved significantly by 1% and 0.17% on the UHDB31 dataset and the IJB-A dataset, respectively.

##### Abstract (translated by Google)
本文着重于在不改变网络架构的情况下改进当前卷积神经网络在视觉识别中的性能。提出了一种分层匹配器，它在所有类别标签上的一个全局神经网络之后构建局部二进制神经网络链，称为基于局部分类器链的卷积神经网络（LCC-CNN）。每个样本的签名分为两部分：基于全球网络的全球组成部分;基于本地二进制网络的本地组件。局部网络是基于由相似性矩阵和混淆矩阵创建的标签对构建的。在匹配过程中，每个样本都通过一个全局网络和一个本地网络链来获取其最终匹配以避免错误传播。提议的匹配器已经通过图像识别，字符识别和人脸识别数据集进行了评估。实验结果表明，与仅使用全局深度网络的方法相比，所提出的匹配器实现了更好的性能。与UR2D系统相比，UHDB31数据集和IJB-A数据集的准确度分别提高了1％和0.17％。

##### URL
[http://arxiv.org/abs/1805.02339](http://arxiv.org/abs/1805.02339)

##### PDF
[http://arxiv.org/pdf/1805.02339](http://arxiv.org/pdf/1805.02339)

