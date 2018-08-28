---
layout: post
title: "TreeSegNet: Adaptive Tree CNNs for Subdecimeter Aerial Image Segmentation"
date: 2018-08-25 16:48:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Classification
author: Kai Yue, Lei Yang, Ruirui Li, Wei Hu, Fan Zhang, Wei Li
mathjax: true
---

* content
{:toc}

##### Abstract
For the task of subdecimeter aerial imagery segmentation, fine-grained semantic segmentation results are usually difficult to obtain because of complex remote sensing content and optical conditions. Recently, convolutional neural networks (CNNs) have shown outstanding performance on this task. Although many deep neural network structures and techniques have been applied to improve the accuracy, few have paid attention to better differentiating the easily confused classes. In this paper, we propose TreeSegNet which adopts an adaptive network to increase the classification rate at the pixelwise level. Specifically, based on the infrastructure of DeepUNet, a Tree-CNN block in which each node represents a ResNeXt unit is constructed adaptively according to the confusion matrix and the proposed TreeCutting algorithm. By transporting feature maps through concatenating connections, the Tree-CNN block fuses multiscale features and learns best weights for the model. In experiments on the ISPRS 2D semantic labeling Potsdam dataset, the results obtained by TreeSegNet are better than those of other published state-of-the-art methods. Detailed comparison and analysis show that the improvement brought by the adaptive Tree-CNN block is significant.

##### Abstract (translated by Google)
对于亚光度计航拍图像分割的任务，由于复杂的遥感内容和光学条件，通常很难获得细粒度的语义分割结果。最近，卷积神经网络（CNN）在这项任务中表现出色。尽管已经应用了许多深度神经网络结构和技术来提高准确性，但很少有人注意更好地区分容易混淆的类。在本文中，我们提出TreeSegNet采用自适应网络来提高像素级的分类率。具体地，基于DeepUNet的基础结构，根据混淆矩阵和所提出的TreeCutting算法自适应地构造其中每个节点表示ResNeXt单元的Tree-CNN块。通过连接连接传输特征映射，Tree-CNN块融合多尺度特征并学习模型的最佳权重。在ISPRS 2D语义标签Potsdam数据集的实验中，TreeSegNet获得的结果优于其他已发布的最新方法。详细的比较和分析表明，自适应Tree-CNN块带来的改进是显着的。

##### URL
[http://arxiv.org/abs/1804.10879](http://arxiv.org/abs/1804.10879)

##### PDF
[http://arxiv.org/pdf/1804.10879](http://arxiv.org/pdf/1804.10879)

