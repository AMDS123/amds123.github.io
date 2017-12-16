---
layout: post
title: "Depth Adaptive Deep Neural Network for Semantic Segmentation"
date: 2017-08-05 19:54:59
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Byeongkeun Kang, Yeejin Lee, Truong Q. Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present the depth-adaptive deep neural network using a depth map for semantic segmentation. Typical deep neural networks receive inputs at the predetermined locations regardless of the distance from the camera. This fixed receptive field presents a challenge to generalize the features of objects at various distances in neural networks. Specifically, the predetermined receptive fields are too small at a short distance, and vice versa. To overcome this challenge, we develop a neural network which is able to adapt the receptive field not only for each layer but also for each neuron at spatial locations. To adjust the receptive field, we propose the adaptive perception neuron and the in-layer multiscale neuron. The adaptive perception neuron is to adjust the receptive field at each spatial location using the corresponding depth information. The in-layer multiscale neuron is to apply the different size of the receptive field at each feature space to learn features at multiple scales. By the combination of these neurons, we propose the three fully convolutional neural networks. We demonstrate the effectiveness of the proposed neural networks on the novel hand segmentation dataset for hand-object interaction and publicly available RGB-D dataset for semantic segmentation. The experimental results show that the proposed method outperforms the state-of-the-art methods without any additional layers or pre/post-processing.

##### Abstract (translated by Google)
在这项工作中，我们提出深度自适应深度神经网络使用深度图进行语义分割。典型的深度神经网络在预定位置接收输入，而与摄像机的距离无关。这种固定的接受场对于在神经网络中在不同距离处概括物体的特征提出了挑战。具体而言，预定的感受野在短距离处太小，反之亦然。为了克服这个挑战，我们开发了一个神经网络，它能够适应感受野不仅对每一层，而且对每个神经元在空间位置。为了调整感受野，我们提出了自适应感知神经元和层内多尺度神经元。自适应感知神经元是使用相应的深度信息来调整每个空间位置处的感受野。层内多尺度神经元将在每个特征空间处应用不同大小的感受野来学习多尺度的特征。通过这些神经元的组合，我们提出了三个完全卷积神经网络。我们证明了所提出的神经网络在用于手 - 对象交互的新颖的手分割数据集和用于语义分割的公开可用的RGB-D数据集上的有效性。实验结果表明，所提出的方法胜过最先进的方法，没有任何额外的层或前/后处理。

##### URL
[https://arxiv.org/abs/1708.01818](https://arxiv.org/abs/1708.01818)

##### PDF
[https://arxiv.org/pdf/1708.01818](https://arxiv.org/pdf/1708.01818)

