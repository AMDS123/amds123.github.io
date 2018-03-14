---
layout: post
title: "Multimodal Recurrent Neural Networks with Information Transfer Layers for Indoor Scene Labeling"
date: 2018-03-13 09:08:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation RNN
author: Abrar H. Abdulnabi, Bing Shuai, Zhen Zuo, Lap-Pui Chau, Gang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new method called Multimodal RNNs for RGB-D scene semantic segmentation. It is optimized to classify image pixels given two input sources: RGB color channels and Depth maps. It simultaneously performs training of two recurrent neural networks (RNNs) that are crossly connected through information transfer layers, which are learnt to adaptively extract relevant cross-modality features. Each RNN model learns its representations from its own previous hidden states and transferred patterns from the other RNNs previous hidden states; thus, both model-specific and crossmodality features are retained. We exploit the structure of quad-directional 2D-RNNs to model the short and long range contextual information in the 2D input image. We carefully designed various baselines to efficiently examine our proposed model structure. We test our Multimodal RNNs method on popular RGB-D benchmarks and show how it outperforms previous methods significantly and achieves competitive results with other state-of-the-art works.

##### Abstract (translated by Google)
本文提出了一种新的RGB-D场景语义分割多模态RNN方法。它针对给定两个输入源的图像像素进行了优化：RGB颜色通道和深度图。它同时执行通过信息传输层交叉连接的两个循环神经网络（RNN）的训练，其被学习为自适应地提取相关的交叉模态特征。每个RNN模型从它自己以前的隐藏状态中学习它的表示，并从其他RNN的先前隐藏状态转移模式;因此，保留了特定模型和交叉模态特征。我们利用四维2D-RNN的结构来模拟2D输入图像中的短距离和长距离上下文信息。我们仔细设计了各种基线，以有效检查我们提出的模型结构。我们在广受欢迎的RGB-D基准测试中测试了我们的多模RNNs方法，并展示了它如何显着优于以前的方法，并与其他最先进的作品取得了有竞争力的结果。

##### URL
[http://arxiv.org/abs/1803.04687](http://arxiv.org/abs/1803.04687)

##### PDF
[http://arxiv.org/pdf/1803.04687](http://arxiv.org/pdf/1803.04687)

