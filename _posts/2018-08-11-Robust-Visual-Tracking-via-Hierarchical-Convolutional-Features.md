---
layout: post
title: "Robust Visual Tracking via Hierarchical Convolutional Features"
date: 2018-08-11 06:02:26
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Detection Relation Recognition
author: Chao Ma, Jia-Bin Huang, Xiaokang Yang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to exploit the rich hierarchical features of deep convolutional neural networks to improve the accuracy and robustness of visual tracking. Deep neural networks trained on object recognition datasets consist of multiple convolutional layers. These layers encode target appearance with different levels of abstraction. For example, the outputs of the last convolutional layers encode the semantic information of targets and such representations are invariant to significant appearance variations. However, their spatial resolutions are too coarse to precisely localize the target. In contrast, features from earlier convolutional layers provide more precise localization but are less invariant to appearance changes. We interpret the hierarchical features of convolutional layers as a nonlinear counterpart of an image pyramid representation and explicitly exploit these multiple levels of abstraction to represent target objects. Specifically, we learn adaptive correlation filters on the outputs from each convolutional layer to encode the target appearance. We infer the maximum response of each layer to locate targets in a coarse-to-fine manner. To further handle the issues with scale estimation and re-detecting target objects from tracking failures caused by heavy occlusion or out-of-the-view movement, we conservatively learn another correlation filter, that maintains a long-term memory of target appearance, as a discriminative classifier. We apply the classifier to two types of object proposals: (1) proposals with a small step size and tightly around the estimated location for scale estimation; and (2) proposals with large step size and across the whole image for target re-detection. Extensive experimental results on large-scale benchmark datasets show that the proposed algorithm performs favorably against state-of-the-art tracking methods.

##### Abstract (translated by Google)
在本文中，我们提出利用深度卷积神经网络的丰富层次特征来提高视觉跟踪的准确性和鲁棒性。在物体识别数据集上训练的深度神经网络由多个卷积层组成。这些层以不同的抽象级别编码目标外观。例如，最后卷积层的输出编码目标的语义信息，并且这种表示对于显着的外观变化是不变的。但是，它们的空间分辨率太粗糙，无法精确定位目标。相比之下，早期卷积层的特征提供了更精确的定位，但对外观变化的不变性较小。我们将卷积层的层次特征解释为图像金字塔表示的非线性对应物，并明确利用这些多层次的抽象来表示目标对象。具体来说，我们在每个卷积层的输出上学习自适应相关滤波器以编码目标外观。我们推断每个层的最大响应以粗略到精细的方式定位目标。为了进一步处理尺度估计和重新检测目标对象的问题，从跟踪重度遮挡或视野外运动引起的故障，我们保守地学习另一个相关滤波器，它保持目标外观的长期记忆，如判别分类器。我们将分类器应用于两种类型的对象提议：（1）具有小步长并紧紧围绕估计位置进行尺度估计的提议; （2）具有大步长和整个图像的提议，用于目标重新检测。对大规模基准数据集的广泛实验结果表明，所提出的算法对最先进的跟踪方法有利。

##### URL
[http://arxiv.org/abs/1707.03816](http://arxiv.org/abs/1707.03816)

##### PDF
[http://arxiv.org/pdf/1707.03816](http://arxiv.org/pdf/1707.03816)

