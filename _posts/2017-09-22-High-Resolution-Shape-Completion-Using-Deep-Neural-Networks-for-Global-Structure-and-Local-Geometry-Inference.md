---
layout: post
title: "High-Resolution Shape Completion Using Deep Neural Networks for Global Structure and Local Geometry Inference"
date: 2017-09-22 05:16:17
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference RNN Deep_Learning Quantitative
author: Xiaoguang Han, Zhen Li, Haibin Huang, Evangelos Kalogerakis, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a data-driven method for recovering miss-ing parts of 3D shapes. Our method is based on a new deep learning architecture consisting of two sub-networks: a global structure inference network and a local geometry refinement network. The global structure inference network incorporates a long short-term memorized context fusion module (LSTM-CF) that infers the global structure of the shape based on multi-view depth information provided as part of the input. It also includes a 3D fully convolutional (3DFCN) module that further enriches the global structure representation according to volumetric information in the input. Under the guidance of the global structure network, the local geometry refinement network takes as input lo-cal 3D patches around missing regions, and progressively produces a high-resolution, complete surface through a volumetric encoder-decoder architecture. Our method jointly trains the global structure inference and local geometry refinement networks in an end-to-end manner. We perform qualitative and quantitative evaluations on six object categories, demonstrating that our method outperforms existing state-of-the-art work on shape completion.

##### Abstract (translated by Google)
我们提出了一种数据驱动的方法来恢复3D形状的缺失部分。我们的方法基于一个由两个子网络组成的新的深度学习架构：一个全局结构推理网络和一个局部几何细化网络。全局结构推理网络包含一个长期的短期记忆上下文融合模块（LSTM-CF），该模块基于作为输入的一部分提供的多视点深度信息来推断形状的全局结构。它还包括一个3D全卷积（3DFCN）模块，根据输入中的体积信息进一步丰富全局结构表示。在全局结构网络的指导下，局部几何细化网络将缺失区域周围的三维贴片作为输入，通过体积式编码器 - 解码器架构逐步产生高分辨率，完整的表面。我们的方法以端到端的方式联合训练全局结构推理和局部几何细化网络。我们对六个对象类别进行定性和定量评估，证明我们的方法胜过现有的最佳形状完成工作。

##### URL
[https://arxiv.org/abs/1709.07599](https://arxiv.org/abs/1709.07599)

##### PDF
[https://arxiv.org/pdf/1709.07599](https://arxiv.org/pdf/1709.07599)

