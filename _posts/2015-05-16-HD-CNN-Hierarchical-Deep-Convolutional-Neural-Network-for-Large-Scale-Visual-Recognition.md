---
layout: post
title: "HD-CNN: Hierarchical Deep Convolutional Neural Network for Large Scale Visual Recognition"
date: 2015-05-16 03:36:32
categories: arXiv_AI
tags: arXiv_AI Embedding CNN Image_Classification Classification Recognition
author: Zhicheng Yan, Hao Zhang, Robinson Piramuthu, Vignesh Jagadeesh, Dennis DeCoste, Wei Di, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In image classification, visual separability between different object categories is highly uneven, and some categories are more difficult to distinguish than others. Such difficult categories demand more dedicated classifiers. However, existing deep convolutional neural networks (CNN) are trained as flat N-way classifiers, and few efforts have been made to leverage the hierarchical structure of categories. In this paper, we introduce hierarchical deep CNNs (HD-CNNs) by embedding deep CNNs into a category hierarchy. An HD-CNN separates easy classes using a coarse category classifier while distinguishing difficult classes using fine category classifiers. During HD-CNN training, component-wise pretraining is followed by global finetuning with a multinomial logistic loss regularized by a coarse category consistency term. In addition, conditional executions of fine category classifiers and layer parameter compression make HD-CNNs scalable for large-scale visual recognition. We achieve state-of-the-art results on both CIFAR100 and large-scale ImageNet 1000-class benchmark datasets. In our experiments, we build up three different HD-CNNs and they lower the top-1 error of the standard CNNs by 2.65%, 3.1% and 1.1%, respectively.

##### Abstract (translated by Google)
在图像分类中，不同对象类别之间的视觉可分性非常不均衡，有些类别比其他类别更难以区分。这些困难的类别需要更多的专用分类器。然而，现有的深度卷积神经网络（CNN）被训练为平坦的N路分类器，并且很少有人利用类别的层次结构。在本文中，我们通过将深度CNN嵌入到类别层次结构中来引入分层深度CNN（HD-CNN）。 HD-CNN使用粗分类分类器分离易分类，同时使用精分类分类器区分难分类。在HD-CNN培训期间，组件式预训练之后是全局微调，其中多项式逻辑损失由粗类别一致性项调整。此外，精细类别分类器和图层参数压缩的条件执行使得HD-CNN可以进行大规模视觉识别。我们在CIFAR100和大型ImageNet 1000级基准数据集上实现了最新的结果。在我们的实验中，我们建立了三种不同的HD-CNN，他们分别将标准CNN的前1误差分别降低了2.65％，3.1％和1.1％。

##### URL
[http://arxiv.org/abs/1410.0736](http://arxiv.org/abs/1410.0736)

##### PDF
[http://arxiv.org/pdf/1410.0736](http://arxiv.org/pdf/1410.0736)

