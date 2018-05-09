---
layout: post
title: "Image Ordinal Classification and Understanding: Grid Dropout with Masking Label"
date: 2018-05-08 08:58:54
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Relation
author: Chao Zhang, Ce Zhu, Jimin Xiao, Xun Xu, Yipeng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Image ordinal classification refers to predicting a discrete target value which carries ordering correlation among image categories. The limited size of labeled ordinal data renders modern deep learning approaches easy to overfit. To tackle this issue, neuron dropout and data augmentation were proposed which, however, still suffer from over-parameterization and breaking spatial structure, respectively. To address the issues, we first propose a grid dropout method that randomly dropout/blackout some areas of the raining image. Then we combine the objective of predicting the blackout patches with classification to take advantage of the spatial information. Finally we demonstrate the effectiveness of both approaches by visualizing the Class Activation Map (CAM) and discover that grid dropout is more aware of the whole facial areas and more robust than neuron dropout for small training dataset. Experiments are conducted on a challenging age estimation dataset - Adience dataset with very competitive results compared with state-of-the-art methods.

##### Abstract (translated by Google)
图像序数分类是指预测一个离散的目标值，它携带图像类别之间的排序相关性。标记的有序数据的有限大小使现代的深度学习方法容易过度拟合。为了解决这个问题，提出了神经元丢失和数据增强，然而，它们仍然分别受到过度参数化和破坏空间结构的影响。为了解决这些问题，我们首先提出了一种网格丢失方法，该方法可随机丢弃/中断下雨图像的某些区域。然后，我们将预测停电补丁的目标与分类相结合，以利用空间信息。最后，我们通过对类激活图（CAM）进行可视化，发现两种方法的有效性，并发现网格丢失对于小型训练数据集更全面地了解整个面部区域并且比神经元退出更加稳健。实验是在具有挑战性的年龄估计数据集上进行的 -  Adience数据集与最先进的方法相比具有非常有竞争力的结果。

##### URL
[https://arxiv.org/abs/1805.02901](https://arxiv.org/abs/1805.02901)

##### PDF
[https://arxiv.org/pdf/1805.02901](https://arxiv.org/pdf/1805.02901)

