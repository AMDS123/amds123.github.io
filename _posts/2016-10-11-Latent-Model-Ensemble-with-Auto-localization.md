---
layout: post
title: "Latent Model Ensemble with Auto-localization"
date: 2016-10-11 01:57:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection Recognition
author: Miao Sun, Tony X. Han, Xun Xu, Ming-Chang Liu, Ahmad Khodayari-Rostamabad
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNN) have exhibited superior performance in many visual recognition tasks including image classification, object detection, and scene label- ing, due to their large learning capacity and resistance to overfit. For the image classification task, most of the current deep CNN- based approaches take the whole size-normalized image as input and have achieved quite promising results. Compared with the previously dominating approaches based on feature extraction, pooling, and classification, the deep CNN-based approaches mainly rely on the learning capability of deep CNN to achieve superior results: the burden of minimizing intra-class variation while maximizing inter-class difference is entirely dependent on the implicit feature learning component of deep CNN; we rely upon the implicitly learned filters and pooling component to select the discriminative regions, which correspond to the activated neurons. However, if the irrelevant regions constitute a large portion of the image of interest, the classification performance of the deep CNN, which takes the whole image as input, can be heavily affected. To solve this issue, we propose a novel latent CNN framework, which treats the most discriminate region as a latent variable. We can jointly learn the global CNN with the latent CNN to avoid the aforementioned big irrelevant region issue, and our experimental results show the evident advantage of the proposed latent CNN over traditional deep CNN: latent CNN outperforms the state-of-the-art performance of deep CNN on standard benchmark datasets including the CIFAR-10, CIFAR- 100, MNIST and PASCAL VOC 2007 Classification dataset.

##### Abstract (translated by Google)
深卷积神经网络（CNN）在许多视觉识别任务中展现了出众的性能，包括图像分类，物体检测和场景标注等。对于图像分类任务，目前大多数基于CNN的深度处理方法都是以整个尺度归一化图像作为输入，取得了很好的效果。与先前基于特征提取，共享和分类的主导方法相比，基于CNN的深度学习方法主要依靠深度CNN的学习能力来获得更好的结果：尽量减少类内变异，同时使类间差异最大化完全依赖深层CNN的隐式特征学习;我们依靠隐式学习的过滤器和合并组件来选择与激活的神经元相对应的区分区域。然而，如果不相关的区域构成大部分感兴趣的图像，则将以整个图像作为输入的深度CNN的分类性能可能受到严重影响。为了解决这个问题，我们提出了一个新的潜在CNN框架，把最区别的区域当作一个潜在的变量。我们可以共同学习全球CNN与潜在的CNN，以避免上述的大无关紧要的区域问题，我们的实验结果表明，提出的潜在的CNN比传统的深CNN有明显的优势：潜在的CNN胜过最先进的性能包括CIFAR-10，CIFAR-100，MNIST和PASCAL VOC 2007分类数据集在内的标准基准数据集的CNN深度。

##### URL
[https://arxiv.org/abs/1604.04333](https://arxiv.org/abs/1604.04333)

##### PDF
[https://arxiv.org/pdf/1604.04333](https://arxiv.org/pdf/1604.04333)

