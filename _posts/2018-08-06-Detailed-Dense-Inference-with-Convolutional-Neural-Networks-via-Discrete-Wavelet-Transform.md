---
layout: post
title: "Detailed Dense Inference with Convolutional Neural Networks via Discrete Wavelet Transform"
date: 2018-08-06 11:57:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Prediction
author: Lingni Ma, Jörg Stückler, Tao Wu, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Dense pixelwise prediction such as semantic segmentation is an up-to-date challenge for deep convolutional neural networks (CNNs). Many state-of-the-art approaches either tackle the loss of high-resolution information due to pooling in the encoder stage, or use dilated convolutions or high-resolution lanes to maintain detailed feature maps and predictions. Motivated by the structural analogy between multi-resolution wavelet analysis and the pooling/unpooling layers of CNNs, we introduce discrete wavelet transform (DWT) into the CNN encoder-decoder architecture and propose WCNN. The high-frequency wavelet coefficients are computed at encoder, which are later used at the decoder to unpooled jointly with coarse-resolution feature maps through the inverse DWT. The DWT/iDWT is further used to develop two wavelet pyramids to capture the global context, where the multi-resolution DWT is applied to successively reduce the spatial resolution and increase the receptive field. Experiment with the Cityscape dataset, the proposed WCNNs are computationally efficient and yield improvements the accuracy for high-resolution dense pixelwise prediction.

##### Abstract (translated by Google)
诸如语义分割的密集像素预测是深度卷积神经网络（CNN）的最新挑战。许多最先进的方法要么解决由于编码器阶段中的池而导致的高分辨率信息的丢失，要么使用扩张的卷积或高分辨率的通道来维护详细的特征图和预测。由于多分辨率小波分析与CNN的合并/解集层之间的结构类比，我们将离散小波变换（DWT）引入CNN编码器 - 解码器架构并提出WCNN。在编码器处计算高频小波系数，其稍后在解码器处通过逆DWT与粗分辨率特征图联合地解卷。 DWT / iDWT进一步用于开发两个小波金字塔以捕获全局背景，其中应用多分辨率DWT以连续降低空间分辨率并增加感受野。使用Cityscape数据集进行实验，所提出的WCNN在计算上是高效的，并且提高了高分辨率密集像素预测的准确性。

##### URL
[https://arxiv.org/abs/1808.01834](https://arxiv.org/abs/1808.01834)

##### PDF
[https://arxiv.org/pdf/1808.01834](https://arxiv.org/pdf/1808.01834)

