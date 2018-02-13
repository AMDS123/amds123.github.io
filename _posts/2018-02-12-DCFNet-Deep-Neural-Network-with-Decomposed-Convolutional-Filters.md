---
layout: post
title: "DCFNet: Deep Neural Network with Decomposed Convolutional Filters"
date: 2018-02-12 15:58:54
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Qiang Qiu, Xiuyuan Cheng, Robert Calderbank, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Filters in a Convolutional Neural Network (CNN) contain model parameters learned from enormous amounts of data. In this paper, we suggest to decompose convolutional filters in CNN as a truncated expansion with pre-fixed bases, namely the Decomposed Convolutional Filters network (DCFNet), where the expansion coefficients remain learned from data. Such a structure not only reduces the number of trainable parameters and computation, but also imposes filter regularity by bases truncation. Through extensive experiments, we consistently observe that DCFNet maintains accuracy for image classification tasks with a significant reduction of model parameters, particularly with Fourier-Bessel (FB) bases, and even with random bases. Theoretically, we analyze the representation stability of DCFNet with respect to input variations, and prove representation stability under generic assumptions on the expansion coefficients. The analysis is consistent with the empirical observations.

##### Abstract (translated by Google)
卷积神经网络（CNN）中的滤波器包含从大量数据中学习的模型参数。在本文中，我们建议将CNN中的卷积滤波器分解为具有预先固定基的截断扩展，即分解卷积滤波器网络（DCFNet），其中展开系数仍然从数据中学习。这样的结构不仅减少了可训练参数和计算次数，而且通过基截断强加了滤波器的规律性。通过广泛的实验，我们始终如一地观察到DCFNet可以保持图像分类任务的准确性，同时显着降低模型参数，特别是傅立叶 - 贝塞尔（FB）基数，甚至随机基数。理论上，我们分析了DCFNet关于输入变量的表示稳定性，并且证明了对扩张系数的一般假设下的表示稳定性。分析与经验观察一致。

##### URL
[http://arxiv.org/abs/1802.04145](http://arxiv.org/abs/1802.04145)

##### PDF
[http://arxiv.org/pdf/1802.04145](http://arxiv.org/pdf/1802.04145)

