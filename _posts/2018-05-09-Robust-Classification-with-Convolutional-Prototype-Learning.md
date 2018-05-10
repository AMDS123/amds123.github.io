---
layout: post
title: "Robust Classification with Convolutional Prototype Learning"
date: 2018-05-09 09:55:45
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial CNN Image_Classification Classification Recognition
author: Hong-Ming Yang, Xu-Yao Zhang, Fei Yin, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have been widely used for image classification. Despite its high accuracies, CNN has been shown to be easily fooled by some adversarial examples, indicating that CNN is not robust enough for pattern classification. In this paper, we argue that the lack of robustness for CNN is caused by the softmax layer, which is a totally discriminative model and based on the assumption of closed world (i.e., with a fixed number of categories). To improve the robustness, we propose a novel learning framework called convolutional prototype learning (CPL). The advantage of using prototypes is that it can well handle the open world recognition problem and therefore improve the robustness. Under the framework of CPL, we design multiple classification criteria to train the network. Moreover, a prototype loss (PL) is proposed as a regularization to improve the intra-class compactness of the feature representation, which can be viewed as a generative model based on the Gaussian assumption of different classes. Experiments on several datasets demonstrate that CPL can achieve comparable or even better results than traditional CNN, and from the robustness perspective, CPL shows great advantages for both the rejection and incremental category learning tasks.

##### Abstract (translated by Google)
卷积神经网络（CNN）已被广泛用于图像分类。尽管CNN具有很高的准确性，但它已被证明容易被一些对抗性例子所迷惑，这表明CNN在模式分类方面不够健壮。在本文中，我们认为CNN缺乏鲁棒性是由softmax层引起的，softmax层是一个完全区分的模型，并基于封闭世界的假设（即具有固定数目的类别）。为了提高鲁棒性，我们提出了一种叫做卷积原型学习（CPL）的新型学习框架。使用原型的优点是它可以很好地处理开放世界的识别问题，从而提高鲁棒性。在CPL的框架下，我们设计了多种分类标准来训练网络。此外，提出了原型损失（PL）作为正则化来改善特征表示的类内紧致性，其可以被视为基于不同类别的高斯假设的生成模型。在几个数据集上进行的实验表明，CPL可以实现与传统CNN相当甚至更好的结果，并且从稳健性角度来看，CPL对拒绝和增量类别学习任务显示出很大的优势。

##### URL
[http://arxiv.org/abs/1805.03438](http://arxiv.org/abs/1805.03438)

##### PDF
[http://arxiv.org/pdf/1805.03438](http://arxiv.org/pdf/1805.03438)

