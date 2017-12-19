---
layout: post
title: "Recurrent Image Captioner: Describing Images with Spatial-Invariant Transformation and Attention Filtering"
date: 2016-12-15 07:19:46
categories: arXiv_CV
tags: arXiv_CV Image_Caption Salient Attention Caption Inference RNN
author: Hao Liu, Yang Yang, Fumin Shen, Lixin Duan, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Along with the prosperity of recurrent neural network in modelling sequential data and the power of attention mechanism in automatically identify salient information, image captioning, a.k.a., image description, has been remarkably advanced in recent years. Nonetheless, most existing paradigms may suffer from the deficiency of invariance to images with different scaling, rotation, etc.; and effective integration of standalone attention to form a holistic end-to-end system. In this paper, we propose a novel image captioning architecture, termed Recurrent Image Captioner (\textbf{RIC}), which allows visual encoder and language decoder to coherently cooperate in a recurrent manner. Specifically, we first equip CNN-based visual encoder with a differentiable layer to enable spatially invariant transformation of visual signals. Moreover, we deploy an attention filter module (differentiable) between encoder and decoder to dynamically determine salient visual parts. We also employ bidirectional LSTM to preprocess sentences for generating better textual representations. Besides, we propose to exploit variational inference to optimize the whole architecture. Extensive experimental results on three benchmark datasets (i.e., Flickr8k, Flickr30k and MS COCO) demonstrate the superiority of our proposed architecture as compared to most of the state-of-the-art methods.

##### Abstract (translated by Google)
随着循环神经网络在顺序数据建模方面的繁荣和自动识别显着信息的注意力机制，近年来图像字幕等图像描述技术得到了显着的发展。尽管如此，大多数现有的范式可能会受到不同尺度，旋转等影像不变性的不足的影响。有效整合独立的注意力，形成整体端到端的体系。在本文中，我们提出了一个新的图像字幕体系结构，称为复发图像标题（\ textbf {RIC}），它允许视觉编码器和语言解码器以一种循环的方式协调合作。具体而言，我们首先配备了基于CNN的视觉编码器，具有可微分层以实现视觉信号的空间不变量变换。此外，我们在编码器和解码器之间部署了一个注意滤波器模块（可微分），以动态确定显着的视觉部分。我们还使用双向LSTM来预处理句子以生成更好的文本表示。此外，我们建议利用变分推理来优化整个架构。在三个基准数据集（即Flickr8k，Flickr30k和MS COCO）上的广泛的实验结果证明了我们提出的架构与大多数最先进的方法相比的优越性。

##### URL
[https://arxiv.org/abs/1612.04949](https://arxiv.org/abs/1612.04949)

##### PDF
[https://arxiv.org/pdf/1612.04949](https://arxiv.org/pdf/1612.04949)

