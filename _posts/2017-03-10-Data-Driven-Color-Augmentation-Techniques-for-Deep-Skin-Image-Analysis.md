---
layout: post
title: "Data-Driven Color Augmentation Techniques for Deep Skin Image Analysis"
date: 2017-03-10 14:39:11
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Adrian Galdran, Aitor Alvarez-Gila, Maria Ines Meyer, Cristina L. Saratxaga, Teresa Araújo, Estibaliz Garrote, Guilherme Aresta, Pedro Costa, A.M. Mendonça, Aurélio Campilho
mathjax: true
---

* content
{:toc}

##### Abstract
Dermoscopic skin images are often obtained with different imaging devices, under varying acquisition conditions. In this work, instead of attempting to perform intensity and color normalization, we propose to leverage computational color constancy techniques to build an artificial data augmentation technique suitable for this kind of images. Specifically, we apply the \emph{shades of gray} color constancy technique to color-normalize the entire training set of images, while retaining the estimated illuminants. We then draw one sample from the distribution of training set illuminants and apply it on the normalized image. We employ this technique for training two deep convolutional neural networks for the tasks of skin lesion segmentation and skin lesion classification, in the context of the ISIC 2017 challenge and without using any external dermatologic image set. Our results on the validation set are promising, and will be supplemented with extended results on the hidden test set when available.

##### Abstract (translated by Google)
在不同的采集条件下，通常使用不同的成像设备获得皮肤镜皮肤图像。在这项工作中，我们不是尝试执行强度和颜色标准化，而是建议利用计算颜色常量技术来构建适合这种图像的人造数据增强技术。具体来说，我们应用灰色阴影颜色常数技术对整个训练集进行颜色归一化，同时保留估计的光源。然后，我们从训练集光源的分布中抽取一个样本，并将其应用于归一化图像。我们采用这种技术来训练两个深度卷积神经网络，用于皮肤病灶分割和皮肤病变分类的任务，在ISIC 2017挑战的背景下，不使用任何外部皮肤病学图像集。我们在验证集上的结果是有希望的，并且在隐藏的测试集可用的情况下将会补充更多的结果。

##### URL
[https://arxiv.org/abs/1703.03702](https://arxiv.org/abs/1703.03702)

##### PDF
[https://arxiv.org/pdf/1703.03702](https://arxiv.org/pdf/1703.03702)

