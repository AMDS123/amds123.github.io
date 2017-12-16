---
layout: post
title: "Understanding Convolution for Semantic Segmentation"
date: 2017-11-09 01:12:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Deep_Learning Prediction
author: Panqu Wang, Pengfei Chen, Ye Yuan, Ding Liu, Zehua Huang, Xiaodi Hou, Garrison Cottrell
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning, especially deep convolutional neural networks (CNNs), have led to significant improvement over previous semantic segmentation systems. Here we show how to improve pixel-wise semantic segmentation by manipulating convolution-related operations that are of both theoretical and practical value. First, we design dense upsampling convolution (DUC) to generate pixel-level prediction, which is able to capture and decode more detailed information that is generally missing in bilinear upsampling. Second, we propose a hybrid dilated convolution (HDC) framework in the encoding phase. This framework 1) effectively enlarges the receptive fields (RF) of the network to aggregate global information; 2) alleviates what we call the "gridding issue" caused by the standard dilated convolution operation. We evaluate our approaches thoroughly on the Cityscapes dataset, and achieve a state-of-art result of 80.1% mIOU in the test set at the time of submission. We also have achieved state-of-the-art overall on the KITTI road estimation benchmark and the PASCAL VOC2012 segmentation task. Our source code can be found at this https URL

##### Abstract (translated by Google)
近来深度学习的进展，尤其是深度卷积神经网络（CNNs），已经比以前的语义分割系统有了显着的改进。在这里我们展示了如何通过操作卷积相关的操作来提高像素方式的语义分割，这些操作既具有理论价值，也具有实用价值。首先，我们设计密集的上采样卷积（DUC）来生成像素级预测，它能够捕获和解码在双线性上采样中通常缺少的更详细的信息。其次，我们在编码阶段提出了一个混合扩张卷积（HDC）框架。这个框架1）有效地扩大网络的接受域（RF）以聚合全球信息; 2）减轻了我们所说的由标准膨胀卷积运算引起的“网格问题”。我们在Cityscapes数据集中彻底评估我们的方法，并在提交时达到测试集中80.1％mIOU的最新结果。我们还在KITTI道路评估基准和PASCAL VOC2012分段任务方面取得了最先进的成果。我们的源代码可以在https网址找到

##### URL
[https://arxiv.org/abs/1702.08502](https://arxiv.org/abs/1702.08502)

##### PDF
[https://arxiv.org/pdf/1702.08502](https://arxiv.org/pdf/1702.08502)

