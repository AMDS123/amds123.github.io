---
layout: post
title: "Design of Kernels in Convolutional Neural Networks for Image Classification"
date: 2016-11-29 04:11:58
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Relation
author: Zhun Sun, Mete Ozay, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the effectiveness of Convolutional Neural Networks (CNNs) for image classification, our understanding of the relationship between shape of convolution kernels and learned representations is limited. In this work, we explore and employ the relationship between shape of kernels which define Receptive Fields (RFs) in CNNs for learning of feature representations and image classification. For this purpose, we first propose a feature visualization method for visualization of pixel-wise classification score maps of learned features. Motivated by our experimental results, and observations reported in the literature for modeling of visual systems, we propose a novel design of shape of kernels for learning of representations in CNNs. In the experimental results, we achieved a state-of-the-art classification performance compared to a base CNN model [28] by reducing the number of parameters and computational time of the model using the ILSVRC-2012 dataset [24]. The proposed models also outperform the state-of-the-art models employed on the CIFAR-10/100 datasets [12] for image classification. Additionally, we analyzed the robustness of the proposed method to occlusion for classification of partially occluded images compared with the state-of-the-art methods. Our results indicate the effectiveness of the proposed approach. The code is available in github.com/minogame/caffe-qhconv.

##### Abstract (translated by Google)
尽管卷积神经网络（CNN）用于图像分类的有效性，但我们对卷积核形状与学习表示之间的关系的理解是有限的。在这项工作中，我们探索和使用内核形状之间的关系，定义CNNs中的接受域（RFs）用于学习特征表示和图像分类。为此，我们首先提出了一种用于可视化学习特征的像素明智分类分数图的特征可视化方法。受到我们的实验结果的启发，以及文献中为视觉系统建模所观察到的观察结果，我们提出了一种用于在CNN中表示学习的核形状的新颖设计。在实验结果中，我们通过使用ILSVRC-2012数据集减少了模型的参数和计算时间[24]，与基本的CNN模型[28]相比，我们实现了最先进的分类性能。所提出的模型也超越了CIFAR-10/100数据集[12]中采用的用于图像分类的最新模型。另外，与最先进的方法相比，我们分析了所提出的方法对部分遮挡图像进行遮挡的鲁棒性。我们的结果表明了所提出方法的有效性。代码可在github.com/minogame/caffe-qhconv中找到。

##### URL
[https://arxiv.org/abs/1511.09231](https://arxiv.org/abs/1511.09231)

##### PDF
[https://arxiv.org/pdf/1511.09231](https://arxiv.org/pdf/1511.09231)

