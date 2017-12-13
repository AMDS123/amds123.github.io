---
layout: post
title: "End-to-end Video-level Representation Learning for Action Recognition"
date: 2017-12-12 06:59:34
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition Represenation_Learning Deep_Learning Recognition
author: Jiagang Zhu, Wei Zou, Zheng Zhu, Lin Li
mathjax: true
---

* content
{:toc}

##### Abstract
From the frame/clip-level feature learning to the video-level representation building, deep learning methods in action recognition have developed rapidly in recent years. However, current methods suffer from the confusion caused by partial observation training, or without end-to-end learning, or restricted to single temporal scale modeling and so on. In this paper, we build upon two-stream ConvNets and propose Deep networks with Temporal Pyramid Pooling (DTPP), an end-to-end video-level representation learning approach, to address these problems. Specifically, at first, RGB images and optical flow stacks are sparsely sampled across the whole video. Then a temporal pyramid pooling layer is used to aggregate the frame-level features which consist of spatial and temporal cues. Lastly, the trained model has compact video-level representation with multiple temporal scales, which is both global and sequence-aware. Experimental results show that DTPP achieves the state-of-the-art performance on two challenging video action datasets: UCF101 and HMDB51, either by ImageNet pre-training or Kinetics pre-training.

##### Abstract (translated by Google)
从帧/片段级特征学习到视频级代表性构建，近年来行为识别中的深度学习方法发展迅速。然而，目前的方法存在部分观察训练引起的混淆，或者没有端到端的学习，或者局限于单时间尺度建模等等。在本文中，我们建立在双流ConvNets之上，并提出了一种端到端视频级表示学习方法Temporary Pyramid Pooling（DTPP）的深度网络来解决这些问题。具体来说，首先在整个视频中对RGB图像和光流栈进行稀疏采样。然后，使用时间金字塔池化层来聚合由空间和时间线索组成的帧级特征。最后，训练模型具有紧凑的视频级表示，具有多个时间尺度，这是全局的和序列感知的。实验结果表明，DTPP通过ImageNet预训练或动力学预训练，在两个具有挑战性的视频动作数据集UCF101和HMDB51上达到了最先进的性能。

##### URL
[http://arxiv.org/abs/1711.04161](http://arxiv.org/abs/1711.04161)

##### PDF
[http://arxiv.org/pdf/1711.04161](http://arxiv.org/pdf/1711.04161)

