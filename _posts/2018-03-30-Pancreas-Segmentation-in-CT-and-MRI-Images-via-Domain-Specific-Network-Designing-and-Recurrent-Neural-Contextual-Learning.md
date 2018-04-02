---
layout: post
title: "Pancreas Segmentation in CT and MRI Images via Domain Specific Network Designing and Recurrent Neural Contextual Learning"
date: 2018-03-30 01:31:53
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Inference RNN Prediction Quantitative
author: Jinzheng Cai, Le Lu, Fuyong Xing, Lin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic pancreas segmentation in radiology images, eg., computed tomography (CT) and magnetic resonance imaging (MRI), is frequently required by computer-aided screening, diagnosis, and quantitative assessment. Yet pancreas is a challenging abdominal organ to segment due to the high inter-patient anatomical variability in both shape and volume metrics. Recently, convolutional neural networks (CNNs) have demonstrated promising performance on accurate segmentation of pancreas. However, the CNN-based method often suffers from segmentation discontinuity for reasons such as noisy image quality and blurry pancreatic boundary. From this point, we propose to introduce recurrent neural networks (RNNs) to address the problem of spatial non-smoothness of inter-slice pancreas segmentation across adjacent image slices. To inference initial segmentation, we first train a 2D CNN sub-network, where we modify its network architecture with deep-supervision and multi-scale feature map aggregation so that it can be trained from scratch with small-sized training data and presents superior performance than transferred models. Thereafter, the successive CNN outputs are processed by another RNN sub-network, which refines the consistency of segmented shapes. More specifically, the RNN sub-network consists convolutional long short-term memory (CLSTM) units in both top-down and bottom-up directions, which regularizes the segmentation of an image by integrating predictions of its neighboring slices. We train the stacked CNN-RNN model end-to-end and perform quantitative evaluations on both CT and MRI images.

##### Abstract (translated by Google)
计算机辅助筛查，诊断和定量评估通常需要放射科图像中的自动胰腺分割，例如计算机断层扫描（CT）和磁共振成像（MRI）。然而，胰腺是一种具有挑战性的腹部器官，由于形状和体积指标中的高患者间解剖变异性而被分割。最近，卷积神经网络（CNN）在精确分割胰腺方面表现出有前途的性能。然而，基于CNN的方法由于诸如嘈杂的图像质量和模糊的胰腺边界等原因经常遭受分割不连续性。从这一点，我们建议引入递归神经网络（RNN）来解决跨相邻图像切片的切片间胰腺分割的空间不平滑问题。为了推断初始分割，我们首先训练一个二维CNN子网络，在那里我们用深度监督和多尺度特征映射聚合来修改其网络体系结构，从而可以从头开始用小规模训练数据进行训练，并呈现出优越的性能比传输的模型。此后，连续的CNN输出由另一个RNN子网络处理，这改善了分段形状的一致性。更具体地说，RNN子网络包括自顶向下和自下而上的卷积长短期记忆（CLSTM）单元，其通过整合其相邻切片的预测来调整图像的分割。我们对堆叠的CNN-RNN模型进行端对端培训，并对CT和MRI图像进行定量评估。

##### URL
[https://arxiv.org/abs/1803.11303](https://arxiv.org/abs/1803.11303)

##### PDF
[https://arxiv.org/pdf/1803.11303](https://arxiv.org/pdf/1803.11303)

