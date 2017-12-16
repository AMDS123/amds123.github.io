---
layout: post
title: "Joint Sequence Learning and Cross-Modality Convolution for 3D Biomedical Segmentation"
date: 2017-04-25 15:54:56
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Deep_Learning
author: Kuan-Lun Tseng, Yen-Liang Lin, Winston Hsu, Chung-Yang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models such as convolutional neural net- work have been widely used in 3D biomedical segmentation and achieve state-of-the-art performance. However, most of them often adapt a single modality or stack multiple modalities as different input channels. To better leverage the multi- modalities, we propose a deep encoder-decoder structure with cross-modality convolution layers to incorporate different modalities of MRI data. In addition, we exploit convolutional LSTM to model a sequence of 2D slices, and jointly learn the multi-modalities and convolutional LSTM in an end-to-end manner. To avoid converging to the certain labels, we adopt a re-weighting scheme and two-phase training to handle the label imbalance. Experimental results on BRATS-2015 show that our method outperforms state-of-the-art biomedical segmentation approaches.

##### Abstract (translated by Google)
卷积神经网络等深度学习模型已被广泛应用于三维生物医学分割领域，并取得了最先进的性能。然而，他们大多数往往适应单一模式或堆叠多种形式作为不同的输入渠道。为了更好地利用多模式，我们提出了一种具有跨模式卷积层的深度编码器 - 解码器结构，以结合不同的MRI数据模式。另外，我们利用卷积LSTM对一系列2D切片进行建模，并以端到端的方式共同学习多模态和卷积LSTM。为了避免收敛到某些标签，我们采用重新加权方案和两阶段训练来处理标签不平衡。 BRATS-2015的实验结果表明，我们的方法胜过了最先进的生物医学分割方法。

##### URL
[https://arxiv.org/abs/1704.07754](https://arxiv.org/abs/1704.07754)

##### PDF
[https://arxiv.org/pdf/1704.07754](https://arxiv.org/pdf/1704.07754)

