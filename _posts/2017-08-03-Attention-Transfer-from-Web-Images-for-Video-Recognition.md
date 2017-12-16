---
layout: post
title: "Attention Transfer from Web Images for Video Recognition"
date: 2017-08-03 02:41:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Action_Recognition CNN Deep_Learning Recognition
author: Junnan Li, Yongkang Wong, Qi Zhao, Mohan Kankanhalli
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep learning based video classifiers for action recognition requires a large amount of labeled videos. The labeling process is labor-intensive and time-consuming. On the other hand, large amount of weakly-labeled images are uploaded to the Internet by users everyday. To harness the rich and highly diverse set of Web images, a scalable approach is to crawl these images to train deep learning based classifier, such as Convolutional Neural Networks (CNN). However, due to the domain shift problem, the performance of Web images trained deep classifiers tend to degrade when directly deployed to videos. One way to address this problem is to fine-tune the trained models on videos, but sufficient amount of annotated videos are still required. In this work, we propose a novel approach to transfer knowledge from image domain to video domain. The proposed method can adapt to the target domain (i.e. video data) with limited amount of training data. Our method maps the video frames into a low-dimensional feature space using the class-discriminative spatial attention map for CNNs. We design a novel Siamese EnergyNet structure to learn energy functions on the attention maps by jointly optimizing two loss functions, such that the attention map corresponding to a ground truth concept would have higher energy. We conduct extensive experiments on two challenging video recognition datasets (i.e. TVHI and UCF101), and demonstrate the efficacy of our proposed method.

##### Abstract (translated by Google)
训练基于深度学习的动作识别视频分类器需要大量的带标签的视频。标签过程劳动强度大，耗时。另一方面，每天都有大量的弱标签图片被用户上传到互联网上。为了利用丰富多样的Web图像集，可伸缩的方法是抓取这些图像来训练基于深度学习的分类器，例如卷积神经网络（CNN）。然而，由于域名转移问题，训练深度分类器的Web图像的性能在直接部署到视频时倾向于降低。解决这个问题的一种方法是对视频上的训练模型进行微调，但仍然需要足够数量的带注释的视频。在这项工作中，我们提出了一种将图像域知识转化为视频域的新方法。所提出的方法可以适应具有有限量的训练数据的目标域（即视频数据）。我们的方法将视频帧映射到一个低维的特征空间，使用CNN的类别区分空间注意图。我们设计了一种新颖的连体能量网结构，通过对两个损失函数进行联合优化来学习关注图上的能量函数，使得对应于地面真值概念的注意图具有更高的能量。我们对两个具有挑战性的视频识别数据集（即TVHI和UCF101）进行了广泛的实验，并展示了我们提出的方法的功效。

##### URL
[https://arxiv.org/abs/1708.00973](https://arxiv.org/abs/1708.00973)

##### PDF
[https://arxiv.org/pdf/1708.00973](https://arxiv.org/pdf/1708.00973)

