---
layout: post
title: "Batch-normalized Maxout Network in Network"
date: 2015-11-09 07:09:57
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jia-Ren Chang, Yong-Sheng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper reports a novel deep architecture referred to as Maxout network In Network (MIN), which can enhance model discriminability and facilitate the process of information abstraction within the receptive field. The proposed network adopts the framework of the recently developed Network In Network structure, which slides a universal approximator, multilayer perceptron (MLP) with rectifier units, to exact features. Instead of MLP, we employ maxout MLP to learn a variety of piecewise linear activation functions and to mediate the problem of vanishing gradients that can occur when using rectifier units. Moreover, batch normalization is applied to reduce the saturation of maxout units by pre-conditioning the model and dropout is applied to prevent overfitting. Finally, average pooling is used in all pooling layers to regularize maxout MLP in order to facilitate information abstraction in every receptive field while tolerating the change of object position. Because average pooling preserves all features in the local patch, the proposed MIN model can enforce the suppression of irrelevant information during training. Our experiments demonstrated the state-of-the-art classification performance when the MIN model was applied to MNIST, CIFAR-10, and CIFAR-100 datasets and comparable performance for SVHN dataset.

##### Abstract (translated by Google)
本文报道了一种新的深层网络结构，称为Maxout网络（MIN），它可以增强模型的可辨识性，并且促进接受领域内的信息抽象过程。所提出的网络采用最近开发的Network In Network结构的框架，其将具有整流器单元的通用逼近器，多层感知器（MLP）滑动到精确特征。我们采用最大MLP来代替MLP来学习各种分段线性激活函数，并调解使用整流器单元时可能发生的消失梯度问题。此外，通过对模型进行预处理来应用批量归一化来减少maxout单元的饱和​​，并且应用丢失来防止过拟合。最后，在所有汇聚层中使用平均汇聚来调整最大MLP，以便在每个接受场中促进信息抽象，同时容忍对象位置的变化。由于平均汇集保留了本地补丁中的所有特征，所以提出的MIN模型可以在训练过程中强制抑制不相关的信息。当MIN模型应用于MNIST，CIFAR-10和CIFAR-100数据集时，我们的实验证明了最新的分类性能和SVHN数据集的可比性能。

##### URL
[https://arxiv.org/abs/1511.02583](https://arxiv.org/abs/1511.02583)

##### PDF
[https://arxiv.org/pdf/1511.02583](https://arxiv.org/pdf/1511.02583)

