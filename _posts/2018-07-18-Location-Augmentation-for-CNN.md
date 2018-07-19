---
layout: post
title: "Location Augmentation for CNN"
date: 2018-07-18 17:16:42
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Semantic_Segmentation
author: Zhenyi Wang, Olga Veksler
mathjax: true
---

* content
{:toc}

##### Abstract
CNNs have made a tremendous impact on the field of computer vision in the last several years. The main component of any CNN architecture is the convolution operation, which is translation invariant by design. However, location in itself can be an important cue. For example, a salient object is more likely to be closer to the center of the image, the sky in the top part of an image, etc. To include the location cue for feature learning, we propose to augment the color image, the usual input to CNNs, with one or more channels that carry location information. We test two approaches for adding location information. In the first approach, we incorporate location directly, by including the row and column indexes as two additional channels to the input image. In the second approach, we add location less directly by adding distance transform from the center pixel as an additional channel to the input image. We perform experiments with both direct and indirect ways to encode location. We show the advantage of augmenting the standard color input with location related channels on the tasks of salient object segmentation, semantic segmentation, and scene parsing.

##### Abstract (translated by Google)
CNN在过去几年中对计算机视觉领域产生了巨大影响。任何CNN架构的主要组成部分是卷积操作，它是设计的平移不变量。但是，位置本身可能是一个重要的线索。例如，显着对象更可能更接近图像的中心，图像顶部的天空等。要包括特征学习的位置提示，我们建议增加彩色图像，通常CNN输入，带有一个或多个携带位置信息的通道。我们测试了两种添加位置信息的方法。在第一种方法中，我们通过将行和列索引作为两个附加通道包含在输入图像中来直接合并位置。在第二种方法中，我们通过将距中心像素的距离变换作为附加通道添加到输入图像来更少地直接添加位置。我们使用直接和间接方式进行实验来编码位置。我们展示了在显着对象分割，语义分割和场景解析的任务中增加具有位置相关通道的标准颜色输入的优点。

##### URL
[https://arxiv.org/abs/1807.07044](https://arxiv.org/abs/1807.07044)

##### PDF
[https://arxiv.org/pdf/1807.07044](https://arxiv.org/pdf/1807.07044)

