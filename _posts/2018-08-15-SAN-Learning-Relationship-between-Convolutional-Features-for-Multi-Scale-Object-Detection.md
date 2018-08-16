---
layout: post
title: "SAN: Learning Relationship between Convolutional Features for Multi-Scale Object Detection"
date: 2018-08-15 05:35:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Relation
author: Yonghyun Kim, Bong-Nam Kang, Daijin Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the recent successful methods in accurate object detection build on the convolutional neural networks (CNN). However, due to the lack of scale normalization in CNN-based detection methods, the activated channels in the feature space can be completely different according to a scale and this difference makes it hard for the classifier to learn samples. We propose a Scale Aware Network (SAN) that maps the convolutional features from the different scales onto a scale-invariant subspace to make CNN-based detection methods more robust to the scale variation, and also construct a unique learning method which considers purely the relationship between channels without the spatial information for the efficient learning of SAN. To show the validity of our method, we visualize how convolutional features change according to the scale through a channel activation matrix and experimentally show that SAN reduces the feature differences in the scale space. We evaluate our method on VOC PASCAL and MS COCO dataset. We demonstrate SAN by conducting several experiments on structures and parameters. The proposed SAN can be generally applied to many CNN-based detection methods to enhance the detection accuracy with a slight increase in the computing time.

##### Abstract (translated by Google)
大多数最近成功的精确物体检测方法建立在卷积神经网络（CNN）上。然而，由于基于CNN的检测方法缺乏尺度归一化，特征空间中的激活通道可能根据比例完全不同，并且这种差异使得分类器难以学习样本。我们提出了一种规模感知网络（SAN），它将来自不同尺度的卷积特征映射到尺度不变的子空间，使基于CNN的检测方法对尺度变化更加稳健，并且还构建了一种独特的学习方法，纯粹考虑了这种关系。在没有空间信息的通道之间进行SAN的有效学习。为了显示我们方法的有效性，我们通过通道激活矩阵可视化卷积特征如何根据比例变化，并通过实验证明SAN减少了比例空间中的特征差异。我们评估了我们对VOC PASCAL和MS COCO数据集的方法。我们通过对结构和参数进行多次实验来演示SAN。所提出的SAN通常可以应用于许多基于CNN的检测方法，以通过略微增加计算时间来提高检测精度。

##### URL
[http://arxiv.org/abs/1808.04974](http://arxiv.org/abs/1808.04974)

##### PDF
[http://arxiv.org/pdf/1808.04974](http://arxiv.org/pdf/1808.04974)

