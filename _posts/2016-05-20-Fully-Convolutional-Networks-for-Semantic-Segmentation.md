---
layout: post
title: "Fully Convolutional Networks for Semantic Segmentation"
date: 2016-05-20 04:30:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Classification Prediction
author: Evan Shelhamer, Jonathan Long, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks are powerful visual models that yield hierarchies of features. We show that convolutional networks by themselves, trained end-to-end, pixels-to-pixels, improve on the previous best result in semantic segmentation. Our key insight is to build "fully convolutional" networks that take input of arbitrary size and produce correspondingly-sized output with efficient inference and learning. We define and detail the space of fully convolutional networks, explain their application to spatially dense prediction tasks, and draw connections to prior models. We adapt contemporary classification networks (AlexNet, the VGG net, and GoogLeNet) into fully convolutional networks and transfer their learned representations by fine-tuning to the segmentation task. We then define a skip architecture that combines semantic information from a deep, coarse layer with appearance information from a shallow, fine layer to produce accurate and detailed segmentations. Our fully convolutional network achieves improved segmentation of PASCAL VOC (30% relative improvement to 67.2% mean IU on 2012), NYUDv2, SIFT Flow, and PASCAL-Context, while inference takes one tenth of a second for a typical image.

##### Abstract (translated by Google)
卷积网络是强大的可视化模型，可以产生特征的层次结构。我们展示了卷积网络自身的训练，端到端，像素到像素，改善了以前在语义分割的最好结果。我们的关键洞察是建立“完全卷积”网络，以任意大小的输入和有效的推理和学习产生相应大小的输出。我们定义和详细说明完全卷积网络的空间，解释它们在空间密集预测任务中的应用，并且绘制与先前模型的连接。我们将现代分类网络（AlexNet，VGG网和GoogLeNet）调整到完全卷积网络，并通过微调将他们的学习表示转移到分割任务。然后，我们定义一个跳过体系结构，将来自深层粗略层的语义信息与浅层精细层的外观信息相结合，以生成准确和详细的分段。我们的完全卷积网络实现了改进的PASCAL VOC（相对于2012年平均IU的30％相对于67.2％IU），NYUDv2，SIFT Flow和PASCAL-Context的分割，而对于典型图像，推断需要十分之一秒。

##### URL
[https://arxiv.org/abs/1605.06211](https://arxiv.org/abs/1605.06211)

##### PDF
[https://arxiv.org/pdf/1605.06211](https://arxiv.org/pdf/1605.06211)

