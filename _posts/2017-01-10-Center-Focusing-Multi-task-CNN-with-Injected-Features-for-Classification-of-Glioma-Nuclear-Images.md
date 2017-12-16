---
layout: post
title: "Center-Focusing Multi-task CNN with Injected Features for Classification of Glioma Nuclear Images"
date: 2017-01-10 18:44:32
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification
author: Veda Murthy, Le Hou, Dimitris Samaras, Tahsin M. Kurc, Joel H. Saltz
mathjax: true
---

* content
{:toc}

##### Abstract
Classifying the various shapes and attributes of a glioma cell nucleus is crucial for diagnosis and understanding the disease. We investigate automated classification of glioma nuclear shapes and visual attributes using Convolutional Neural Networks (CNNs) on pathology images of automatically segmented nuclei. We propose three methods that improve the performance of a previously-developed semi-supervised CNN. First, we propose a method that allows the CNN to focus on the most important part of an image- the image's center containing the nucleus. Second, we inject (concatenate) pre-extracted VGG features into an intermediate layer of our Semi-Supervised CNN so that during training, the CNN can learn a set of complementary features. Third, we separate the losses of the two groups of target classes (nuclear shapes and attributes) into a single-label loss and a multi-label loss so that the prior knowledge of inter-label exclusiveness can be incorporated. On a dataset of 2078 images, the proposed methods combined reduce the error rate of attribute and shape classification by 21.54% and 15.07% respectively compared to the existing state-of-the-art method on the same dataset.

##### Abstract (translated by Google)
分类神经胶质瘤细胞核的各种形状和属性对于诊断和理解疾病是至关重要的。我们调查自动分类神经胶质瘤核形状和视觉属性使用卷积神经网络（CNNs）自动分割核的病理图像。我们提出了三种改进先前开发的半监督CNN的性能的方法。首先，我们提出一种允许CNN专注于图像最重要部分的方法 - 包含核的图像中心。其次，我们将预先提取的VGG特征注入（连接）到我们的半监督CNN的中间层，以便在训练期间，CNN可以学习一组互补特征。第三，我们将两组目标类别（核形状和属性）的损失分为单标签丢失和多标签丢失，从而可以结合先前关于标签间排他性的知识。在2078幅图像的数据集上，与同一数据集上现有的最新方法相比，所提出的方法相结合，将属性和形状分类的错误率分别降低了21.54％和15.07％。

##### URL
[https://arxiv.org/abs/1612.06825](https://arxiv.org/abs/1612.06825)

##### PDF
[https://arxiv.org/pdf/1612.06825](https://arxiv.org/pdf/1612.06825)

