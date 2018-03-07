---
layout: post
title: "ExpandNet: A Deep Convolutional Neural Network for High Dynamic Range Expansion from Low Dynamic Range Content"
date: 2018-03-06 15:56:51
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Demetris Marnerides, Thomas Bashford-Rogers, Jonathan Hatchett, Kurt Debattista
mathjax: true
---

* content
{:toc}

##### Abstract
High dynamic range (HDR) imaging provides the capability of handling real world lighting as opposed to the traditional low dynamic range (LDR) which struggles to accurately represent images with higher dynamic range. However, most imaging content is still available only in LDR. This paper presents a method for generating HDR content from LDR content based on deep Convolutional Neural Networks (CNNs) termed ExpandNet. ExpandNet accepts LDR images as input and generates images with an expanded range in an end-to-end fashion. The model attempts to reconstruct missing information that was lost from the original signal due to quantization, clipping, tone mapping or gamma correction. The added information is reconstructed from learned features, as the network is trained in a supervised fashion using a dataset of HDR images. The approach is fully automatic and data driven; it does not require any heuristics or human expertise. ExpandNet uses a multiscale architecture which avoids the use of upsampling layers to improve image quality. The method performs well compared to expansion/inverse tone mapping operators quantitatively on multiple metrics, even for badly exposed inputs.

##### Abstract (translated by Google)
与传统的低动态范围（LDR）相比，高动态范围（HDR）成像提供了处理真实世界光照的能力，传统的低动态范围努力准确地表示具有更高动态范围的图像。但是，大多数成像内容仍然只能在LDR中使用。本文介绍了一种基于称为ExpandNet的深度卷积神经网络（CNN）从LDR内容生成HDR内容的方法。 ExpandNet接受LDR图像作为输入，并以端到端的方式生成范围扩大的图像。该模型试图重建由于量化，削波，色调映射或伽马校正而从原始信号丢失的丢失信息。所添加的信息是从学习的特征重建的，因为网络使用HDR图像数据集以受监督的方式进行训练。该方法是完全自动的和数据驱动的;它不需要任何启发式或人类专业知识。 ExpandNet使用多尺度架构，避免使用上采样层来提高图像质量。与扩展/逆色调映射运算符相比，该方法在多个度量上定量表现很好，即使对于暴露不良的输入。

##### URL
[http://arxiv.org/abs/1803.02266](http://arxiv.org/abs/1803.02266)

##### PDF
[http://arxiv.org/pdf/1803.02266](http://arxiv.org/pdf/1803.02266)

