---
layout: post
title: "Self-Supervised Intrinsic Image Decomposition"
date: 2017-11-10 03:31:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Prediction
author: Michael Janner, Jiajun Wu, Tejas D. Kulkarni, Ilker Yildirim, Joshua B. Tenenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
Intrinsic decomposition from a single image is a highly challenging task, due to its inherent ambiguity and the scarcity of training data. In contrast to traditional fully supervised learning approaches, in this paper we propose learning intrinsic image decomposition by explaining the input image. Our model, the Rendered Intrinsics Network (RIN), joins together an image decomposition pipeline, which predicts reflectance, shape, and lighting conditions given a single image, with a recombination function, a learned shading model used to recompose the original input based off of intrinsic image predictions. Our network can then use unsupervised reconstruction error as an additional signal to improve its intermediate representations. This allows large-scale unlabeled data to be useful during training, and also enables transferring learned knowledge to images of unseen object categories, lighting conditions, and shapes. Extensive experiments demonstrate that our method performs well on both intrinsic image decomposition and knowledge transfer.

##### Abstract (translated by Google)
由于其固有的模糊性和训练数据的稀缺性，从单个图像进行内在分解是非常具有挑战性的任务。与传统的全监督学习方法相比，本文提出了通过解释输入图像来学习固有图像分解。我们的模型Rendering Intrinsics Network（RIN）将一个图像分解流水线结合在一起，该流水线在给定单个图像的情况下预测反射，形状和光照条件，具有重组函数，学习的阴影模型用于基于内在的图像预测。然后，我们的网络可以使用无监督重建误差作为附加信号来改善其中间表示。这使得大规模的未标记数据在训练中是有用的，并且还能够将学习到的知识转移到看不见的物体类别，照明条件和形状的图像上。大量的实验表明，我们的方法在内在图像分解和知识转移方面表现良好。

##### URL
[https://arxiv.org/abs/1711.03678](https://arxiv.org/abs/1711.03678)

##### PDF
[https://arxiv.org/pdf/1711.03678](https://arxiv.org/pdf/1711.03678)

