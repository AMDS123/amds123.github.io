---
layout: post
title: "Face Attribute Prediction Using Off-the-Shelf CNN Features"
date: 2016-06-21 14:27:33
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning Prediction Recognition Face_Recognition
author: Yang Zhong, Josephine Sullivan, Haibo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting attributes from face images in the wild is a challenging computer vision problem. To automatically describe face attributes from face containing images, traditionally one needs to cascade three technical blocks --- face localization, facial descriptor construction, and attribute classification --- in a pipeline. As a typical classification problem, face attribute prediction has been addressed using deep learning. Current state-of-the-art performance was achieved by using two cascaded Convolutional Neural Networks (CNNs), which were specifically trained to learn face localization and attribute description. In this paper, we experiment with an alternative way of employing the power of deep representations from CNNs. Combining with conventional face localization techniques, we use off-the-shelf architectures trained for face recognition to build facial descriptors. Recognizing that the describable face attributes are diverse, our face descriptors are constructed from different levels of the CNNs for different attributes to best facilitate face attribute prediction. Experiments on two large datasets, LFWA and CelebA, show that our approach is entirely comparable to the state-of-the-art. Our findings not only demonstrate an efficient face attribute prediction approach, but also raise an important question: how to leverage the power of off-the-shelf CNN representations for novel tasks.

##### Abstract (translated by Google)
从野外的人脸图像预测属性是一个具有挑战性的计算机视觉问题。为了从包含图像的脸部自动描述脸部属性，传统上需要将三个技术块（面部定位，面部描述符构建和属性分类）级联在流水线中。作为一个典型的分类问题，人脸属性预测已经用深度学习来解决。目前最先进的性能是通过使用两个级联的卷积神经网络（CNN）来实现的，这些网络经过专门的学习，可以学习人脸定位和属性描述。在本文中，我们尝试了一种使用来自CNN的深度表示的力量的替代方式。结合传统的人脸定位技术，我们使用经过训练的人脸识别架构来建立面部描述符。认识到可描述的人脸属性是多样的，我们的脸描述符是从不同层次的CNNs针对不同属性构建的，以最好地促进人脸属性预测。对两个大数据集LFWA和CelebA的实验表明，我们的方法完全可以与最先进的技术相媲美。我们的研究结果不仅证明了一个有效的人脸属性预测方法，而且还提出了一个重要的问题：如何利用现成的CNN表示的力量为新的任务。

##### URL
[https://arxiv.org/abs/1602.03935](https://arxiv.org/abs/1602.03935)

##### PDF
[https://arxiv.org/pdf/1602.03935](https://arxiv.org/pdf/1602.03935)

