---
layout: post
title: "LSTM-CF: Unifying Context Modeling and Fusion with LSTMs for RGB-D Scene Labeling"
date: 2016-07-26 16:46:43
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Zhen Li, Yukang Gan, Xiaodan Liang, Yizhou Yu, Hui Cheng, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic labeling of RGB-D scenes is crucial to many intelligent applications including perceptual robotics. It generates pixelwise and fine-grained label maps from simultaneously sensed photometric (RGB) and depth channels. This paper addresses this problem by i) developing a novel Long Short-Term Memorized Context Fusion (LSTM-CF) Model that captures and fuses contextual information from multiple channels of photometric and depth data, and ii) incorporating this model into deep convolutional neural networks (CNNs) for end-to-end training. Specifically, contexts in photometric and depth channels are, respectively, captured by stacking several convolutional layers and a long short-term memory layer; the memory layer encodes both short-range and long-range spatial dependencies in an image along the vertical direction. Another long short-term memorized fusion layer is set up to integrate the contexts along the vertical direction from different channels, and perform bi-directional propagation of the fused vertical contexts along the horizontal direction to obtain true 2D global contexts. At last, the fused contextual representation is concatenated with the convolutional features extracted from the photometric channels in order to improve the accuracy of fine-scale semantic labeling. Our proposed model has set a new state of the art, i.e., 48.1% and 49.4% average class accuracy over 37 categories (2.2% and 5.4% improvement) on the large-scale SUNRGBD dataset and the NYUDv2dataset, respectively.

##### Abstract (translated by Google)
RGB-D场景的语义标记对许多智能应用（包括感知机器人）至关重要。它从同时感测的光度测量（RGB）和深度通道生成按像素和细粒度的标签贴图。本文通过以下方式解决了这个问题：1）开发了一种新的长时短时记忆上下文融合（LSTM-CF）模型，该模型捕获和融合来自光度测量和深度数据的多个通道的上下文信息，以及ii）将该模型并入深度卷积神经网络（CNN）进行端到端的培训。具体来说，光度和深度通道中的上下文分别通过堆叠多个卷积层和长的短期存储层来捕获;存储器层沿着垂直方向对图像中的短程和长程空间相关性进行编码。另一个长期的短期记忆融合层被设置为沿着来自不同信道的垂直方向上下文融合，并且沿水平方向执行融合的垂直上下文的双向传播以获得真正的2D全局上下文。最后，将融合的上下文表示与从光度通道提取的卷积特征串联起来，以提高精细语义标注的准确性。我们提出的模型已经建立了一个新的技术水平，即在大型SUNRGBD数据集和NYUDv2数据集上，37个类别（2.2％和5.4％的改进）的平均类别准确率分别为48.1％和49.4％。

##### URL
[https://arxiv.org/abs/1604.05000](https://arxiv.org/abs/1604.05000)

##### PDF
[https://arxiv.org/pdf/1604.05000](https://arxiv.org/pdf/1604.05000)

