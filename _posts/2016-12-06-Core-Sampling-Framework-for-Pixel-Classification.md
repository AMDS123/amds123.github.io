---
layout: post
title: "Core Sampling Framework for Pixel Classification"
date: 2016-12-06 20:28:44
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Transfer_Learning Classification
author: Manohar Karki, Robert DiBiano, Saikat Basu, Supratik Mukhopadhyay
mathjax: true
---

* content
{:toc}

##### Abstract
The intermediate map responses of a Convolutional Neural Network (CNN) contain information about an image that can be used to extract contextual knowledge about it. In this paper, we present a core sampling framework that is able to use these activation maps from several layers as features to another neural network using transfer learning to provide an understanding of an input image. Our framework creates a representation that combines features from the test data and the contextual knowledge gained from the responses of a pretrained network, processes it and feeds it to a separate Deep Belief Network. We use this representation to extract more information from an image at the pixel level, hence gaining understanding of the whole image. We experimentally demonstrate the usefulness of our framework using a pretrained VGG-16 model to perform segmentation on the BAERI dataset of Synthetic Aperture Radar(SAR) imagery and the CAMVID dataset.

##### Abstract (translated by Google)
卷积神经网络（CNN）的中间映射响应包含关于可用于提取关于它的上下文知识的图像的信息。在本文中，我们提出了一个核心抽样框架，能够使用这些激活图从几个层作为特征到另一个神经网络使用传输学习提供了一个输入图像的理解。我们的框架创建了一个表示形式，将来自测试数据的特征与从预训练网络的响应中获得的上下文知识相结合，对其进行处理，并将其馈送到单独的深信网络。我们使用这种表示从像素级的图像中提取更多的信息，从而获得对整个图像的理解。我们通过实验证明了我们的框架的有用性，使用预训练的VGG-16模型来对合成孔径雷达（SAR）图像和CAMVID数据集的BAERI数据集执行分割。

##### URL
[https://arxiv.org/abs/1612.01981](https://arxiv.org/abs/1612.01981)

##### PDF
[https://arxiv.org/pdf/1612.01981](https://arxiv.org/pdf/1612.01981)

