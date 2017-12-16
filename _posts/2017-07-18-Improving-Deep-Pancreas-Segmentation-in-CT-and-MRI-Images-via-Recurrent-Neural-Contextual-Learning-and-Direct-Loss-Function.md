---
layout: post
title: "Improving Deep Pancreas Segmentation in CT and MRI Images via Recurrent Neural Contextual Learning and Direct Loss Function"
date: 2017-07-18 01:33:08
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN RNN Deep_Learning Prediction Quantitative
author: Jinzheng Cai, Le Lu, Yuanpu Xie, Fuyong Xing, Lin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have demonstrated very promising performance on accurate segmentation of challenging organs (e.g., pancreas) in abdominal CT and MRI scans. The current deep learning approaches conduct pancreas segmentation by processing sequences of 2D image slices independently through deep, dense per-pixel masking for each image, without explicitly enforcing spatial consistency constraint on segmentation of successive slices. We propose a new convolutional/recurrent neural network architecture to address the contextual learning and segmentation consistency problem. A deep convolutional sub-network is first designed and pre-trained from scratch. The output layer of this network module is then connected to recurrent layers and can be fine-tuned for contextual learning, in an end-to-end manner. Our recurrent sub-network is a type of Long short-term memory (LSTM) network that performs segmentation on an image by integrating its neighboring slice segmentation predictions, in the form of a dependent sequence processing. Additionally, a novel segmentation-direct loss function (named Jaccard Loss) is proposed and deep networks are trained to optimize Jaccard Index (JI) directly. Extensive experiments are conducted to validate our proposed deep models, on quantitative pancreas segmentation using both CT and MRI scans. Our method outperforms the state-of-the-art work on CT [11] and MRI pancreas segmentation [1], respectively.

##### Abstract (translated by Google)
深度神经网络在精确分割腹部CT和MRI扫描中的具有挑战性的器官（例如胰腺）方面表现出非常有希望的性能。目前的深度学习方法通​​过对每个图像进行深度，密集的每像素掩蔽，独立处理2D图像切片的序列来进行胰腺分割，而不对连续切片的分割明确实施空间一致性约束。我们提出了一种新的卷积/递归神经网络结构来解决上下文学习和分割一致性问题。首先设计一个深度卷积子网络，并从头开始进行预先训练。然后将这个网络模块的输出层连接到循环层，并且可以以端到端的方式进行上下文学习的微调。我们的经常性子网络是一种长期短期记忆（LSTM）网络，它通过集成相邻的切片分割预测，以相关序列处理的形式对图像进行分割。此外，还提出了一种新的分段直接损失函数（称为Jaccard损失），并对深度网络进行训练，以直接优化Jaccard指数（JI）。进行了大量的实验来验证我们提出的深层模型，使用CT和MRI扫描定量胰腺分割。我们的方法分别胜过CT [11]和MRI胰腺分割[1]的最新研究成果。

##### URL
[https://arxiv.org/abs/1707.04912](https://arxiv.org/abs/1707.04912)

##### PDF
[https://arxiv.org/pdf/1707.04912](https://arxiv.org/pdf/1707.04912)

