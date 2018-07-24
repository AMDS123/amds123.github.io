---
layout: post
title: "Region Convolutional Features for Multi-Label Remote Sensing Image Retrieval"
date: 2018-07-23 14:04:18
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Segmentation CNN
author: Weixun Zhou, Xueqing Deng, Zhenfeng Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional remote sensing image retrieval (RSIR) systems usually perform single-label retrieval where each image is annotated by a single label representing the most significant semantic content of the image. This assumption, however, ignores the complexity of remote sensing images, where an image might have multiple classes (i.e., multiple labels), thus resulting in worse retrieval performance. We therefore propose a novel multi-label RSIR approach with fully convolutional networks (FCN). In our approach, we first train a FCN model using a pixel-wise labeled dataset,and the trained FCN is then used to predict the segmentation maps of each image in the considered archive. We finally extract region convolutional features of each image based on its segmentation map.The region features can be either used to perform region-based retrieval or further post-processed to obtain a feature vector for similarity measure. The experimental results show that our approach achieves state-of-the-art performance in contrast to conventional single-label and recent multi-label RSIR approaches.

##### Abstract (translated by Google)
传统的遥感图像检索（RSIR）系统通常执行单标签检索，其中每个图像由表示图像的最重要语义内容的单个标签注释。然而，该假设忽略了遥感图像的复杂性，其中图像可能具有多个类别（即，多个标签），因此导致较差的检索性能。因此，我们提出了一种具有完全卷积网络（FCN）的新型多标签RSIR方法。在我们的方法中，我们首先使用逐像素标记的数据集训练FCN模型，然后使用训练的FCN来预测所考虑的存档中的每个图像的分割图。我们最终基于其分割图提取每个图像的区域卷积特征。区域特征可以用于执行基于区域的检索或者进一步后处理以获得用于相似性度量的特征向量。实验结果表明，与传统的单标签和最近的多标签RSIR方法相比，我们的方法实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1807.08634](http://arxiv.org/abs/1807.08634)

##### PDF
[http://arxiv.org/pdf/1807.08634](http://arxiv.org/pdf/1807.08634)

