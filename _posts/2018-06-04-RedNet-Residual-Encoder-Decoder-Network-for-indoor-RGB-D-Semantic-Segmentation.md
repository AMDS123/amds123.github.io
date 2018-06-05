---
layout: post
title: "RedNet: Residual Encoder-Decoder Network for indoor RGB-D Semantic Segmentation"
date: 2018-06-04 11:33:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Jindong Jiang, Lunan Zheng, Fei Luo, Zhijun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Indoor semantic segmentation has always been a difficult task in computer vision. In this paper, we propose an RGB-D residual encoder-decoder architecture, named RedNet, for indoor RGB-D semantic segmentation. In RedNet, the residual module is applied to both the encoder and decoder as the basic building block, and the skip-connection is used to bypass the spatial feature between the encoder and decoder. In order to incorporate the depth information of the scene, a fusion structure is constructed, which makes inference on RGB image and depth image separately, and fuses their features over several layers. In order to efficiently optimize the network's parameters, we propose a `pyramid supervision' training scheme, which applies supervised learning over different layers in the decoder, to cope with the problem of gradients vanishing. Experiment results show that the proposed RedNet(ResNet-50) achieves a state-of-the-art mIoU accuracy of 47.8\% on the SUN RGB-D benchmark dataset.

##### Abstract (translated by Google)
室内语义分割一直是计算机视觉中的一项难题。在本文中，我们提出了一个名为RedNet的RGB-D残余编码器 - 解码器架构，用于室内RGB-D语义分割。在RedNet中，残差模块作为基本构建块应用于编码器和解码器，跳过连接用于绕过编码器和解码器之间的空间特征。为了融合场景的深度信息，构建了一个融合结构，分别对RGB图像和深度图像进行推理，并将其特征融合到多个层次上。为了有效地优化网络参数，我们提出了一种“金字塔监督”训练方案，在解码器的不同层次上应用监督学习，以解决梯度消失的问题。实验结果表明，建议的RedNet（ResNet-50）在SUN RGB-D基准数据集上实现了47.8％的最新mIoU精度。

##### URL
[http://arxiv.org/abs/1806.01054](http://arxiv.org/abs/1806.01054)

##### PDF
[http://arxiv.org/pdf/1806.01054](http://arxiv.org/pdf/1806.01054)

