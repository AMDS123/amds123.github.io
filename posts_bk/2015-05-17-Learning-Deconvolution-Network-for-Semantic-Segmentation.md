---
layout: post
title: "Learning Deconvolution Network for Semantic Segmentation"
date: 2015-05-17 07:33:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: Hyeonwoo Noh, Seunghoon Hong, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel semantic segmentation algorithm by learning a deconvolution network. We learn the network on top of the convolutional layers adopted from VGG 16-layer net. The deconvolution network is composed of deconvolution and unpooling layers, which identify pixel-wise class labels and predict segmentation masks. We apply the trained network to each proposal in an input image, and construct the final semantic segmentation map by combining the results from all proposals in a simple manner. The proposed algorithm mitigates the limitations of the existing methods based on fully convolutional networks by integrating deep deconvolution network and proposal-wise prediction; our segmentation method typically identifies detailed structures and handles objects in multiple scales naturally. Our network demonstrates outstanding performance in PASCAL VOC 2012 dataset, and we achieve the best accuracy (72.5%) among the methods trained with no external data through ensemble with the fully convolutional network.

##### Abstract (translated by Google)
我们通过学习一个反卷积网络来提出一种新的语义分割算法。我们学习了从VGG 16层网络采用的卷积层之上的网络。去卷积网络由去卷积和去卷积层组成，它们识别按像素分类的标签并预测分割掩模。我们将训练好的网络应用到输入图像中的每个提议中，并通过将所有提议的结果以简单的方式进行组合来构建最终的语义分割图。该算法通过集成深度反卷积网络和建议式预测来缓解基于完全卷积网络的现有方法的局限性;我们的分割方法通常识别详细的结构，并自然处理多个尺度的对象。我们的网络在PASCAL VOC 2012数据集中表现出色，我们通过与完全卷积网络集成，在没有外部数据的训练方法中达到了最高的精度（72.5％）。

##### URL
[https://arxiv.org/abs/1505.04366](https://arxiv.org/abs/1505.04366)

##### PDF
[https://arxiv.org/pdf/1505.04366](https://arxiv.org/pdf/1505.04366)

