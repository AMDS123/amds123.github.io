---
layout: post
title: "Learning Multilayer Channel Features for Pedestrian Detection"
date: 2016-03-01 03:25:45
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Jiale Cao, Yanwei Pang, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Pedestrian detection based on the combination of Convolutional Neural Network (i.e., CNN) and traditional handcrafted features (i.e., HOG+LUV) has achieved great success. Generally, HOG+LUV are used to generate the candidate proposals and then CNN classifies these proposals. Despite its success, there is still room for improvement. For example, CNN classifies these proposals by the full-connected layer features while proposal scores and the features in the inner-layers of CNN are ignored. In this paper, we propose a unifying framework called Multilayer Channel Features (MCF) to overcome the drawback. It firstly integrates HOG+LUV with each layer of CNN into a multi-layer image channels. Based on the multi-layer image channels, a multi-stage cascade AdaBoost is then learned. The weak classifiers in each stage of the multi-stage cascade is learned from the image channels of corresponding layer. With more abundant features, MCF achieves the state-of-the-art on Caltech pedestrian dataset (i.e., 10.40% miss rate). Using new and accurate annotations, MCF achieves 7.98% miss rate. As many non-pedestrian detection windows can be quickly rejected by the first few stages, it accelerates detection speed by 1.43 times. By eliminating the highly overlapped detection windows with lower scores after the first stage, it's 4.07 times faster with negligible performance loss.

##### Abstract (translated by Google)
基于卷积神经网络（即CNN）和传统手工特征（即HOG + LUV）的组合的行人检测取得了巨大的成功。一般来说，HOG + LUV用于生成候选提案，然后CNN将这些提议分类。尽管取得了成功，但仍有改进的空间。例如，CNN通过全连接层特征对这些提案进行分类，而提案分数和CNN内层的特征则被忽略。在本文中，我们提出了一个称为多层信道特征（MCF）的统一框架来克服这个缺点。它首先将HOG + LUV与每层CNN集成为一个多层图像通道。基于多层图像通道，然后学习多级级联AdaBoost。多级级联的各级弱分类器是从相应层的图像通道中学习的。凭借更丰富的功能，MCF实现了加州理工学院的行人数据集（即10.40％失败率）的最新技术。使用新的和准确的注释，MCF达到7.98％的失败率。由于很多非行人检测窗口可以在前几个阶段快速拒绝，因此检测速度加快了1.43倍。通过消除第一阶段后得分较低的高度重叠的检测窗口，速度提高了4.07倍，性能损失可以忽略不计。

##### URL
[https://arxiv.org/abs/1603.00124](https://arxiv.org/abs/1603.00124)

##### PDF
[https://arxiv.org/pdf/1603.00124](https://arxiv.org/pdf/1603.00124)

