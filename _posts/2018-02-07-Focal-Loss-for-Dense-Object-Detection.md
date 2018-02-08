---
layout: post
title: "Focal Loss for Dense Object Detection"
date: 2018-02-07 18:44:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Detection
author: Tsung-Yi Lin, Priya Goyal, Ross Girshick, Kaiming He, Piotr Doll&#xe1;r
mathjax: true
---

* content
{:toc}

##### Abstract
The highest accuracy object detectors to date are based on a two-stage approach popularized by R-CNN, where a classifier is applied to a sparse set of candidate object locations. In contrast, one-stage detectors that are applied over a regular, dense sampling of possible object locations have the potential to be faster and simpler, but have trailed the accuracy of two-stage detectors thus far. In this paper, we investigate why this is the case. We discover that the extreme foreground-background class imbalance encountered during training of dense detectors is the central cause. We propose to address this class imbalance by reshaping the standard cross entropy loss such that it down-weights the loss assigned to well-classified examples. Our novel Focal Loss focuses training on a sparse set of hard examples and prevents the vast number of easy negatives from overwhelming the detector during training. To evaluate the effectiveness of our loss, we design and train a simple dense detector we call RetinaNet. Our results show that when trained with the focal loss, RetinaNet is able to match the speed of previous one-stage detectors while surpassing the accuracy of all existing state-of-the-art two-stage detectors. Code is at: https://github.com/facebookresearch/Detectron.

##### Abstract (translated by Google)
迄今为止，最高精度的对象检测器是基于R-CNN推广的两阶段方法，其中分类器被应用于候选对象位置的稀疏集合。相比之下，应用在可能的物体位置的规则的密集采样的一级探测器具有更快更简单的潜力，但是到目前为止已经落后于两级探测器的精度。在本文中，我们调查为什么是这样的情况。我们发现在密集探测器训练过程中遇到的极端的前景 - 背景类别失衡是中心原因。我们建议通过重塑标准的交叉熵损失来解决这个类别的不平衡问题，从而降低分类好的例子的损失。我们的小说焦点损失重点集中在一个稀疏的硬例子训练，并防止在训练过程中压倒检测器的大量简单的负面因素。为了评估我们损失的有效性，我们设计和训练一个简单的密度检测器，我们称之为RetinaNet。我们的研究结果表明，在使用焦点损失进行训练时，RetinaNet能够匹配以前的一级探测器的速度，同时超过所有现有最先进的两级探测器的精度。代码在：https：//github.com/facebookresearch/Detectron。

##### URL
[http://arxiv.org/abs/1708.02002](http://arxiv.org/abs/1708.02002)

##### PDF
[http://arxiv.org/pdf/1708.02002](http://arxiv.org/pdf/1708.02002)

