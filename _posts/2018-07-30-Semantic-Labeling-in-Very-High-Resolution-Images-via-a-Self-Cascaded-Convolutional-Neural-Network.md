---
layout: post
title: "Semantic Labeling in Very High Resolution Images via a Self-Cascaded Convolutional Neural Network"
date: 2018-07-30 08:49:25
categories: arXiv_AI
tags: arXiv_AI CNN
author: Yongcheng Liu, Bin Fan, Lingfeng Wang, Jun Bai, Shiming Xiang, Chunhong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic labeling for very high resolution (VHR) images in urban areas, is of significant importance in a wide range of remote sensing applications. However, many confusing manmade objects and intricate fine-structured objects make it very difficult to obtain both coherent and accurate labeling results. For this challenging task, we propose a novel deep model with convolutional neural networks (CNNs), i.e., an end-to-end self-cascaded network (ScasNet). Specifically, for confusing manmade objects, ScasNet improves the labeling coherence with sequential global-to-local contexts aggregation. Technically, multi-scale contexts are captured on the output of a CNN encoder, and then they are successively aggregated in a self-cascaded manner. Meanwhile, for fine-structured objects, ScasNet boosts the labeling accuracy with a coarse-to-fine refinement strategy. It progressively refines the target objects using the low-level features learned by CNN's shallow layers. In addition, to correct the latent fitting residual caused by multi-feature fusion inside ScasNet, a dedicated residual correction scheme is proposed. It greatly improves the effectiveness of ScasNet. Extensive experimental results on three public datasets, including two challenging benchmarks, show that ScasNet achieves the state-of-the-art performance.

##### Abstract (translated by Google)
在城市地区进行高分辨率（VHR）图像的语义标记在广泛的遥感应用中具有重要意义。然而，许多令人困惑的人造物体和复杂的精细结构物体使得很难获得连贯和准确的标记结果。对于这一具有挑战性的任务，我们提出了一种具有卷积神经网络（CNN）的新型深度模型，即端到端自级联网络（ScasNet）。具体而言，为了混淆人造对象，ScasNet通过顺序的全局到本地上下文聚合改进了标签的一致性。从技术上讲，在CNN编码器的输出上捕获多尺度上下文，然后以自级联方式连续聚合它们。同时，对于精细结构的对象，ScasNet通过粗略到精细的细化策略提高了标签的准确性。它使用CNN浅层学习的低级特征逐步细化目标对象。另外，为了校正ScasNet中多特征融合引起的潜在拟合残差，提出了一种专用的残差校正方案。它极大地提高了ScasNet的有效性。三个公共数据集的广泛实验结果，包括两个具有挑战性的基准，表明ScasNet实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1807.11236](http://arxiv.org/abs/1807.11236)

##### PDF
[http://arxiv.org/pdf/1807.11236](http://arxiv.org/pdf/1807.11236)

