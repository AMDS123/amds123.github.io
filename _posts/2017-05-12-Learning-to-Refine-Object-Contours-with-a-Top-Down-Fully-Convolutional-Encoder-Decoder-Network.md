---
layout: post
title: "Learning to Refine Object Contours with a Top-Down Fully Convolutional Encoder-Decoder Network"
date: 2017-05-12 07:52:27
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Detection
author: Yahui Liu, Jian Yao, Li Li, Xiaohu Lu, Jing Han
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a novel deep contour detection algorithm with a top-down fully convolutional encoder-decoder network. Our proposed method, named TD-CEDN, solves two important issues in this low-level vision problem: (1) learning multi-scale and multi-level features; and (2) applying an effective top-down refined approach in the networks. TD-CEDN performs the pixel-wise prediction by means of leveraging features at all layers of the net. Unlike skip connections and previous encoder-decoder methods, we first learn a coarse feature map after the encoder stage in a feedforward pass, and then refine this feature map in a top-down strategy during the decoder stage utilizing features at successively lower layers. Therefore, the deconvolutional process is conducted stepwise, which is guided by Deeply-Supervision Net providing the integrated direct supervision. The above proposed technologies lead to a more precise and clearer prediction. Our proposed algorithm achieved the state-of-the-art on the BSDS500 dataset (ODS F-score of 0.788), the PASCAL VOC2012 dataset (ODS F-score of 0.588), and and the NYU Depth dataset (ODS F-score of 0.735).

##### Abstract (translated by Google)
我们开发了一个新的深度轮廓检测算法与自上而下的完全卷积编码器 - 解码器网络。我们提出的方法，TD-CEDN，解决了这个低层次的视觉问题中的两个重要问题：（1）学习多尺度和多层次的特征;和（2）在网络中应用有效的自顶向下的细化方法。 TD-CEDN通过利用网络各层的特征来执行像素方式的预测。与跳过连接和先前的编码器解码器方法不同，我们首先在前馈通道中学习编码器阶段之后的粗略特征映射，然后在利用连续较低层处的特征的解码器阶段期间在自顶向下策略中优化该特征映射。因此，反卷积过程是逐步进行的，由深度监管网提供综合直接监督。以上提出的技术导致更精确和更清晰的预测。我们提出的算法在BSDS500数据集（ODS F-score 0.788），PASCAL VOC2012数据集（ODS F-score 0.588）以及NYU Depth数据集（ODS F-score of 0.735）。

##### URL
[https://arxiv.org/abs/1705.04456](https://arxiv.org/abs/1705.04456)

##### PDF
[https://arxiv.org/pdf/1705.04456](https://arxiv.org/pdf/1705.04456)

