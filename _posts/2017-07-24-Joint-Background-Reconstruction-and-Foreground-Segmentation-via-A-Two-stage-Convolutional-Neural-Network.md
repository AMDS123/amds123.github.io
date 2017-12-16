---
layout: post
title: "Joint Background Reconstruction and Foreground Segmentation via A Two-stage Convolutional Neural Network"
date: 2017-07-24 14:45:58
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN
author: Xu Zhao, Yingying Chen, Ming Tang, Jinqiao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Foreground segmentation in video sequences is a classic topic in computer vision. Due to the lack of semantic and prior knowledge, it is difficult for existing methods to deal with sophisticated scenes well. Therefore, in this paper, we propose an end-to-end two-stage deep convolutional neural network (CNN) framework for foreground segmentation in video sequences. In the first stage, a convolutional encoder-decoder sub-network is employed to reconstruct the background images and encode rich prior knowledge of background scenes. In the second stage, the reconstructed background and current frame are input into a multi-channel fully-convolutional sub-network (MCFCN) for accurate foreground segmentation. In the two-stage CNN, the reconstruction loss and segmentation loss are jointly optimized. The background images and foreground objects are output simultaneously in an end-to-end way. Moreover, by incorporating the prior semantic knowledge of foreground and background in the pre-training process, our method could restrain the background noise and keep the integrity of foreground objects at the same time. Experiments on CDNet 2014 show that our method outperforms the state-of-the-art by 4.9%.

##### Abstract (translated by Google)
视频序列中的前景分割是计算机视觉中的经典话题。由于缺乏语义和先验知识，现有的方法难以很好地处理复杂的场景。因此，本文提出了一种端到端的两阶段深度卷积神经网络（CNN）视频序列前景分割框架。在第一阶段，卷积编码器 - 解码器子网络被用来重建背景图像并且编码丰富的背景场景的先验知识。在第二阶段，将重建的背景和当前帧输入到多通道全卷积子网络（MCFCN）中以进行精确的前景分割。在两级CNN中，重建损失和分割损失被共同优化。背景图像和前景物体以端到端的方式同时输出。此外，通过在训练过程中融入前景和背景的先验语义知识，可以抑制背景噪声，同时保持前景物体的完整性。 CDNet 2014上的实验表明，我们的方法比现有技术的性能提高了4.9％。

##### URL
[https://arxiv.org/abs/1707.07584](https://arxiv.org/abs/1707.07584)

##### PDF
[https://arxiv.org/pdf/1707.07584](https://arxiv.org/pdf/1707.07584)

