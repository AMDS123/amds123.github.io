---
layout: post
title: "Assessing Shape Bias Property of Convolutional Neural Networks"
date: 2018-03-21 03:54:18
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Hossein Hosseini, Baicen Xiao, Mayoore Jaiswal, Radha Poovendran
mathjax: true
---

* content
{:toc}

##### Abstract
It is known that humans display "shape bias" when classifying new items, i.e., they prefer to categorize objects based on their shape rather than color. Convolutional Neural Networks (CNNs) are also designed to take into account the spatial structure of image data. In fact, experiments on image datasets, consisting of triples of a probe image, a shape-match and a color-match, have shown that one-shot learning models display shape bias as well. 
 In this paper, we examine the shape bias property of CNNs. In order to conduct large scale experiments, we propose using the model accuracy on images with reversed brightness as a metric to evaluate the shape bias property. Such images, called negative images, contain objects that have the same shape as original images, but with different colors. Through extensive systematic experiments, we investigate the role of different factors, such as training data, model architecture, initialization and regularization techniques, on the shape bias property of CNNs. We show that it is possible to design different CNNs that achieve similar accuracy on original images, but perform significantly different on negative images, suggesting that CNNs do not intrinsically display shape bias. We then show that CNNs are able to learn and generalize the structures, when the model is properly initialized or data is properly augmented, and if batch normalization is used.

##### Abstract (translated by Google)
众所周知，人类在分类新项目时显示“形状偏差”，即他们更喜欢根据形状而不是颜色对物体进行分类。卷积神经网络（CNN）也被设计为考虑图像数据的空间结构。事实上，图像数据集上的实验包括探针图像的三元组，形状匹配和颜色匹配，表明单次学习模型也显示形状偏差。
 在本文中，我们研究了CNN的形状偏置特性。为了进行大规模实验，我们建议使用具有反向亮度的图像的模型精度作为度量来评估形状偏差性质。这种称为负图像的图像包含与原始图像具有相同形状但具有不同颜色的对象。通过广泛的系统实验，我们研究了不同因素（如训练数据，模型架构，初始化和正则化技术）对CNN形状偏置特性的作用。我们表明有可能设计不同的CNN在原始图像上达到类似的准确性，但在负面图像上表现明显不同，这表明CNN不会内在地显示形状偏差。然后，我们表明CNNs能够学习和概括结构，当模型正确初始化或数据适当增加时，以及是否使用批量标准化。

##### URL
[http://arxiv.org/abs/1803.07739](http://arxiv.org/abs/1803.07739)

##### PDF
[http://arxiv.org/pdf/1803.07739](http://arxiv.org/pdf/1803.07739)

