---
layout: post
title: "Object Counting with Small Datasets of Large Images"
date: 2018-05-28 18:33:37
categories: arXiv_CV
tags: arXiv_CV CNN
author: Shubhra Aich, Ian Stavness
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the problem of training one-look regression models for counting objects in datasets comprising a small number of high-resolution, variable-shaped images. To reduce overfitting when training on full resolution samples, we propose to use global sum pooling (GSP) instead of global average pooling (GAP) or fully connected (FC) layers at the backend of a convolutional neural network. Although computationally equivalent to GAP, we show via detailed experimentation that GSP allows convolutional networks to learn the counting task as a simple linear mapping problem generalized over the input shape and the number of objects present. We evaluate our approach on four different aerial image datasets - three car counting datasets (CARPK, PUCPR+, and COWC) and one new challenging dataset for wheat spike counting. Our GSP approach achieves state-of-the-art performance on all four datasets and GSP models trained with smaller-sized image patches localize objects better than their GAP counterparts.

##### Abstract (translated by Google)
我们探讨训练一维回归模型的问题，该模型用于对包含少量高分辨率，可变形图像的数据集中的对象进行计数。为了减少训练全分辨率样本时的过拟合问题，我们建议在卷积神经网络的后端使用全局总和池（GSP）而不是全局平均池（GAP）或完全连接（FC）层。尽管在计算上等同于GAP，但我们通过详细的实验显示，GSP允许卷积网络将计数任务作为一个简单的线性映射问题进行学习，该问题笼统地描述了输入形状和存在的对象的数量。我们在四个不同的航空影像数据集上评估我们的方法 - 三个车辆计数数据集（CARPK，PUCPR +和COWC）以及一个用于小麦穗计数的具有挑战性的新数据集。我们的GSP方法在所有四个数据集上实现了最先进的性能，而使用较小尺寸图像修补程序进行训练的GSP模型比其GAP对象更好地定位对象。

##### URL
[http://arxiv.org/abs/1805.11123](http://arxiv.org/abs/1805.11123)

##### PDF
[http://arxiv.org/pdf/1805.11123](http://arxiv.org/pdf/1805.11123)

