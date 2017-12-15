---
layout: post
title: "Learning to Refine Object Segments"
date: 2016-07-26 20:40:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Prediction
author: Pedro O. Pinheiro, Tsung-Yi Lin, Ronan Collobert, Piotr Dollàr
mathjax: true
---

* content
{:toc}

##### Abstract
Object segmentation requires both object-level information and low-level pixel data. This presents a challenge for feedforward networks: lower layers in convolutional nets capture rich spatial information, while upper layers encode object-level knowledge but are invariant to factors such as pose and appearance. In this work we propose to augment feedforward nets for object segmentation with a novel top-down refinement approach. The resulting bottom-up/top-down architecture is capable of efficiently generating high-fidelity object masks. Similarly to skip connections, our approach leverages features at all layers of the net. Unlike skip connections, our approach does not attempt to output independent predictions at each layer. Instead, we first output a coarse `mask encoding' in a feedforward pass, then refine this mask encoding in a top-down pass utilizing features at successively lower layers. The approach is simple, fast, and effective. Building on the recent DeepMask network for generating object proposals, we show accuracy improvements of 10-20% in average recall for various setups. Additionally, by optimizing the overall network architecture, our approach, which we call SharpMask, is 50% faster than the original DeepMask network (under .8s per image).

##### Abstract (translated by Google)
对象分割需要对象级信息和低级像素数据。这对前馈网络提出了挑战：卷积网络中的较低层捕获丰富的空间信息，而较高层编码对象级知识，但是对姿势和外观等因素不变。在这项工作中，我们建议用一种新颖的自顶向下的细化方法来增加用于对象分割的前馈网络。由此产生的自底向上/自顶向下的架构能够高效地生成高保真度的目标掩模。与跳过连接类似，我们的方法利用了网络各层的功能。与跳过连接不同，我们的方法不会尝试输出每一层的独立预测。相反，我们首先在前馈中输出一个粗糙的“掩码编码”，然后利用连续较低层的特征在自顶向下的遍中精炼这个掩码编码。该方法简单，快速，有效。基于最近的DeepMask网络来生成对象提议，我们显示了对于各种设置的平均召回的10-20％的准确度提高。此外，通过优化整体网络架构，我们称之为SharpMask的方法比原始的DeepMask网络（每张图像0.8s以下）快50％。

##### URL
[https://arxiv.org/abs/1603.08695](https://arxiv.org/abs/1603.08695)

##### PDF
[https://arxiv.org/pdf/1603.08695](https://arxiv.org/pdf/1603.08695)

