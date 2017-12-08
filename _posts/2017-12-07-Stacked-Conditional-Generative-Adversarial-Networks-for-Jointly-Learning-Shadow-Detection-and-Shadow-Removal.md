---
layout: post
title: "Stacked Conditional Generative Adversarial Networks for Jointly Learning Shadow Detection and Shadow Removal"
date: 2017-12-07 02:57:38
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection Relation
author: Jifeng Wang, Xiang Li, Le Hui, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding shadows from a single image spontaneously derives into two types of task in previous studies, containing shadow detection and shadow removal. In this paper, we present a multi-task perspective, which is not embraced by any existing work, to jointly learn both detection and removal in an end-to-end fashion that aims at enjoying the mutually improved benefits from each other. Our framework is based on a novel STacked Conditional Generative Adversarial Network (ST-CGAN), which is composed of two stacked CGANs, each with a generator and a discriminator. Specifically, a shadow image is fed into the first generator which produces a shadow detection mask. That shadow image, concatenated with its predicted mask, goes through the second generator in order to recover its shadow-free image consequently. In addition, the two corresponding discriminators are very likely to model higher level relationships and global scene characteristics for the detected shadow region and reconstruction via removing shadows, respectively. More importantly, for multi-task learning, our design of stacked paradigm provides a novel view which is notably different from the commonly used one as the multi-branch version. To fully evaluate the performance of our proposed framework, we construct the first large-scale benchmark with 1870 image triplets (shadow image, shadow mask image, and shadow-free image) under 135 scenes. Extensive experimental results consistently show the advantages of ST-CGAN over several representative state-of-the-art methods on two large-scale publicly available datasets and our newly released one.

##### Abstract (translated by Google)
从以前的研究中理解单个图像中的阴影自发地导出了两种类型的任务，包含阴影检测和阴影去除。在本文中，我们提出了一个多任务的观点，这个观点不被任何已有的工作所包含，共同地学习端到端的检测和去除，旨在享受彼此相互提高的利益。我们的框架是基于一个新颖的STacked Conditional Generative Adversarial Network（ST-CGAN），它由两个堆叠的CGAN组成，每个CGAN都有一个发生器和一个鉴别器。具体而言，将阴影图像馈送到产生阴影检测掩模的第一发生器中。该阴影图像与其预测的掩模连接，通过第二发生器以便随后恢复其无阴影图像。另外，两个相应的鉴别器很可能分别针对检测到的阴影区域和通过去除阴影重建对高层关系和全局场景特征进行建模。更重要的是，对于多任务学习，我们的堆栈范式设计提供了一个新颖的视图，与多分支版本中常用的视图有显着的不同。为了充分评估我们提出的框架的性能，我们在135个场景下构建了第一个具有1870个图像三元组（阴影图像，阴影图像和无阴影图像）的大规模基准。广泛的实验结果在两个大规模公开可用的数据集和我们新发布的数据集上始终如一地显示出ST-CGAN相对于几种具有代表性的最先进方法的优势。

##### URL
[http://arxiv.org/abs/1712.02478](http://arxiv.org/abs/1712.02478)

##### PDF
[http://arxiv.org/pdf/1712.02478](http://arxiv.org/pdf/1712.02478)

