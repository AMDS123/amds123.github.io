---
layout: post
title: "DenseReg: Fully Convolutional Dense Shape Regression In-the-Wild"
date: 2017-06-19 18:51:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Rıza Alp Güler, George Trigeorgis, Epameinondas Antonakos, Patrick Snape, Stefanos Zafeiriou, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose to learn a mapping from image pixels into a dense template grid through a fully convolutional network. We formulate this task as a regression problem and train our network by leveraging upon manually annotated facial landmarks "in-the-wild". We use such landmarks to establish a dense correspondence field between a three-dimensional object template and the input image, which then serves as the ground-truth for training our regression system. We show that we can combine ideas from semantic segmentation with regression networks, yielding a highly-accurate "quantized regression" architecture. Our system, called DenseReg, allows us to estimate dense image-to-template correspondences in a fully convolutional manner. As such our network can provide useful correspondence information as a stand-alone system, while when used as an initialization for Statistical Deformable Models we obtain landmark localization results that largely outperform the current state-of-the-art on the challenging 300W benchmark. We thoroughly evaluate our method on a host of facial analysis tasks and also provide qualitative results for dense human body correspondence. We make our code available at this http URL along with supplementary materials.

##### Abstract (translated by Google)
在本文中，我们建议通过完全卷积网络学习从图像像素到密集模板网格的映射。我们将这个任务作为一个回归问题来制定，并利用手动注释的面部标志“野外”来训练我们的网络。我们使用这样的标志在三维物体模板和输入图像之间建立一个密集的对应场，然后作为训练我们的回归系统的基本事实。我们表明，我们可以将语义分割的思想与回归网络结合起来，产生高度准确的“量化回归”体系结构。我们的系统DenseReg允许我们以完全卷积的方式估计密集的图像到模板的对应关系。因此，我们的网络可以提供有用的对应信息作为一个独立的系统，而当作为统计可变模型的初始化时，我们可以获得具有里程碑意义的本地化结果，这些结果在具有挑战性的300W基准测试中大大优于目前的最新技术水平。我们在大量的面部分析任务上彻底评估了我们的方法，并为密集的人体对应提供了定性的结果。我们在这个http URL中提供我们的代码以及补充材料。

##### URL
[https://arxiv.org/abs/1612.01202](https://arxiv.org/abs/1612.01202)

##### PDF
[https://arxiv.org/pdf/1612.01202](https://arxiv.org/pdf/1612.01202)

