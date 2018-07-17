---
layout: post
title: "Learning Transferable Deep Models for Land-Use Classification with High-Resolution Remote Sensing Images"
date: 2018-07-16 08:02:10
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Xin-Yi Tong, Gui-Song Xia, Qikai Lu, Huanfeng Shen, Shengyang Li, Shucheng You, Liangpei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, large amount of high spatial-resolution remote sensing (HRRS) images are available for land-use mapping. However, due to the complex information brought by the increased spatial resolution and the data disturbances caused by different conditions of image acquisition, it is often difficult to find an efficient method for achieving accurate land-use classification with heterogeneous and high-resolution remote sensing images. In this paper, we propose a scheme to learn transferable deep models for land-use classification with HRRS images. The main idea is to rely on deep neural networks for presenting the semantic information contained in different types of land-uses and propose a pseudo-labeling and sample selection scheme for improving the transferability of deep models. More precisely, a deep Convolutional Neural Networks (CNNs) is first pre-trained with a well-annotated land-use dataset, referred to as the source data. Then, given a target image with no labels, the pre-trained CNN model is utilized to classify the image in a patch-wise manner. The patches with high classification probability are assigned with pseudo-labels and employed as the queries to retrieve related samples from the source data. The pseudo-labels confirmed with the retrieved results are regarded as supervised information for fine-tuning the pre-trained deep model. In order to obtain a pixel-wise land-use classification with the target image, we rely on the fine-tuned CNN and develop a hybrid classification by combining patch-wise classification and hierarchical segmentation. In addition, we create a large-scale land-use dataset containing $150$ Gaofen-2 satellite images for CNN pre-training. Experiments on multi-source HRRS images, including Gaofen-2, Gaofen-1, Jilin-1, Ziyuan-3, and Google Earth images, show encouraging results and demonstrate the efficiency of the proposed scheme.

##### Abstract (translated by Google)
近年来，大量的高空间分辨率遥感（HRRS）图像可用于土地利用制图。然而，由于增加的空间分辨率和由不同的图像采集条件引起的数据干扰带来的复杂信息，通常很难找到一种有效的方法来实现具有异构和高分辨率遥感图像的准确的土地利用分类。在本文中，我们提出了一种方案，用HRRS图像学习土地利用分类的可转移深度模型。主要思想是依靠深度神经网络来呈现不同类型土地利用中包含的语义信息，并提出伪标记和样本选择方案，以提高深层模型的可转移性。更确切地说，深度卷积神经网络（CNN）首先使用注释良好的土地利用数据集进行预训练，称为源数据。然后，给定没有标签的目标图像，利用预训练的CNN模型以贴片方式对图像进行分类。具有高分类概率的补丁被赋予伪标签并用作查询以从源数据中检索相关样本。用检索结果确认的伪标签被视为用于微调预训练深度模型的监督信息。为了获得与目标图像的逐像素的土地利用分类，我们依赖于微调的CNN并通过组合分块分类和分层分割来开发混合分类。此外，我们还制作了一个大型土地利用数据集，其中包含150美元的Gaofen-2卫星图像，用于CNN预训练。多源HRRS图像的实验，包括Gaofen-2，Gaofen-1，Jilin-1，Ziyuan-3和Google Earth图像，显示出令人鼓舞的结果，并证明了所提方案的效率。

##### URL
[http://arxiv.org/abs/1807.05713](http://arxiv.org/abs/1807.05713)

##### PDF
[http://arxiv.org/pdf/1807.05713](http://arxiv.org/pdf/1807.05713)

