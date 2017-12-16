---
layout: post
title: "Do Convolutional Neural Networks Learn Class Hierarchy?"
date: 2017-10-17 21:02:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection Relation
author: Bilal Alsallakh, Amin Jourabloo, Mao Ye, Xiaoming Liu, Liu Ren
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) currently achieve state-of-the-art accuracy in image classification. With a growing number of classes, the accuracy usually drops as the possibilities of confusion increase. Interestingly, the class confusion patterns follow a hierarchical structure over the classes. We present visual-analytics methods to reveal and analyze this hierarchy of similar classes in relation with CNN-internal data. We found that this hierarchy not only dictates the confusion patterns between the classes, it furthermore dictates the learning behavior of CNNs. In particular, the early layers in these networks develop feature detectors that can separate high-level groups of classes quite well, even after a few training epochs. In contrast, the latter layers require substantially more epochs to develop specialized feature detectors that can separate individual classes. We demonstrate how these insights are key to significant improvement in accuracy by designing hierarchy-aware CNNs that accelerate model convergence and alleviate overfitting. We further demonstrate how our methods help in identifying various quality issues in the training data.

##### Abstract (translated by Google)
卷积神经网络（CNN）目前在图像分类方面达到了最先进的精度。随着班级数量的增加，精确度通常会随着混淆的可能性的增加而下降。有趣的是，类混淆模式遵循类的层次结构。我们提出了可视化分析方法来揭示和分析与CNN内部数据相关的类似类的层次结构。我们发现这个层次结构不仅规定了类之间的混淆模式，而且还规定了CNN的学习行为。特别是，这些网络中的早期层次开发了特征检测器，即使经过几个训练时期，也可以很好地分离出高级别的类别组。相比之下，后一层需要更多的时代来开发可以分离各个类别的专用特征检测器。我们通过设计能够加速模型收敛和缓解过度拟合的层次感知型CNN来证明这些洞察力是如何显着提高准确性的关键。我们进一步展示了我们的方法如何帮助确定培训数据中的各种质量问题。

##### URL
[https://arxiv.org/abs/1710.06501](https://arxiv.org/abs/1710.06501)

##### PDF
[https://arxiv.org/pdf/1710.06501](https://arxiv.org/pdf/1710.06501)

