---
layout: post
title: "Image-based Survival Analysis for Lung Cancer Patients using CNNs"
date: 2018-08-29 08:30:46
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction Quantitative
author: Christoph Haarburger, Philippe Weitz, Oliver Rippel, Dorit Merhof
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional survival models such as the Cox proportional hazards model are typically based on scalar or categorical clinical features. With the advent of increasingly large image datasets, it has become feasible to incorporate quantitative image features into survival prediction. So far, this kind of analysis is mostly based on radiomics features, i.e. a fixed set of features that is mathematically defined a priori. In order to capture highly abstract information, it is desirable to learn the feature extraction using convolutional neural networks. However, for tomographic medical images, model training is difficult because on one hand, only few samples of 3D image data fit into one batch at once and on the other hand, survival loss functions are essentially ordering measures that require large batch sizes. In this work, we show that by simplifying survival analysis to median survival classification, convolutional neural networks can be trained with small batch sizes and learn features that predict survival equally well as end-to-end hazard prediction networks. Furthermore, we demonstrate that adding features from a fine-tuned convolutional neural network improves the predictive accuracy of Cox models that otherwise only rely on radiomics features. Moreover, we propose survival label noise as a means of data augmentation for deep image based survival analysis.

##### Abstract (translated by Google)
传统的生存模型，例如Cox比例风险模型，通常基于标量或分类临床特征。随着越来越大的图像数据集的出现，将定量图像特征结合到生存预测中变得可行。到目前为止，这种分析主要基于无线电组学特征，即在数学上先验地定义的一组固定特征。为了捕获高度抽象的信息，期望使用卷积神经网络来学习特征提取。然而，对于断层摄影医学图像，模型训练是困难的，因为一方面，一次只有少数三维图像数据样本适合一批，另一方面，存活损失函数基本上是需要大批量大小的排序测量。在这项工作中，我们表明，通过简化生存分析到中位生存分类，卷积神经网络可以用小批量训练，并学习与端到端危险预测网络一样好地预测生存的特征。此外，我们证明了从微调卷积神经网络中添加特征可以提高Cox模型的预测精度，否则只能依赖于放射组学特征。此外，我们提出生存标签噪声作为基于深度图像的生存分析的数据增加手段。

##### URL
[http://arxiv.org/abs/1808.09679](http://arxiv.org/abs/1808.09679)

##### PDF
[http://arxiv.org/pdf/1808.09679](http://arxiv.org/pdf/1808.09679)

