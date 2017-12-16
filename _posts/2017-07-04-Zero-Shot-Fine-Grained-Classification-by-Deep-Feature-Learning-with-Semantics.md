---
layout: post
title: "Zero-Shot Fine-Grained Classification by Deep Feature Learning with Semantics"
date: 2017-07-04 00:18:32
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Inference Classification
author: Aoxue Li, Zhiwu Lu, Liwei Wang, Tao Xiang, Xinqi Li, Ji-Rong Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained image classification, which aims to distinguish images with subtle distinctions, is a challenging task due to two main issues: lack of sufficient training data for every class and difficulty in learning discriminative features for representation. In this paper, to address the two issues, we propose a two-phase framework for recognizing images from unseen fine-grained classes, i.e. zero-shot fine-grained classification. In the first feature learning phase, we finetune deep convolutional neural networks using hierarchical semantic structure among fine-grained classes to extract discriminative deep visual features. Meanwhile, a domain adaptation structure is induced into deep convolutional neural networks to avoid domain shift from training data to test data. In the second label inference phase, a semantic directed graph is constructed over attributes of fine-grained classes. Based on this graph, we develop a label propagation algorithm to infer the labels of images in the unseen classes. Experimental results on two benchmark datasets demonstrate that our model outperforms the state-of-the-art zero-shot learning models. In addition, the features obtained by our feature learning model also yield significant gains when they are used by other zero-shot learning models, which shows the flexility of our model in zero-shot fine-grained classification.

##### Abstract (translated by Google)
细粒度的图像分类是一个具有挑战性的任务，其目的是通过细微的差别来区分图像，这是一个具有挑战性的任务，因为两个主要问题：每个类缺乏足够的训练数据，难以学习用于表示的区分特征。在本文中，为了解决这两个问题，我们提出了一个两阶段的框架来识别从不可见的细粒度类，即零镜精细粒度分类的图像。在第一个特征学习阶段，我们使用细粒度类中的分层语义结构对深度卷积神经网络进行微调，以提取有区别的深度视觉特征。同时将深度卷积神经网络引入域自适应结构，避免从训练数据向测试数据的转换。在第二个标签推理阶段，一个语义有向图被构造在细粒度类的属性上。基于这个图，我们开发了一个标签传播算法来推断未看类中图像的标签。两个基准数据集上的实验结果表明，我们的模型胜过了最先进的零点学习模型。另外，通过我们的特征学习模型获得的特征在被其他零点学习模型使用时也会产生显着的收益，这表明了我们的模型在零射击细粒度分类中的灵活性。

##### URL
[https://arxiv.org/abs/1707.00785](https://arxiv.org/abs/1707.00785)

##### PDF
[https://arxiv.org/pdf/1707.00785](https://arxiv.org/pdf/1707.00785)

