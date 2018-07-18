---
layout: post
title: "Robust Deep Multi-modal Learning Based on Gated Information Fusion Network"
date: 2018-07-17 05:42:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Jaekyum Kim, Junho Koh, Yecheol Kim, Jaehyung Choi, Youngbae Hwang, Jun Won Choi
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of multi-modal learning is to use complimentary information on the relevant task provided by the multiple modalities to achieve reliable and robust performance. Recently, deep learning has led significant improvement in multi-modal learning by allowing for the information fusion in the intermediate feature levels. This paper addresses a problem of designing robust deep multi-modal learning architecture in the presence of imperfect modalities. We introduce deep fusion architecture for object detection which processes each modality using the separate convolutional neural network (CNN) and constructs the joint feature map by combining the intermediate features from the CNNs. In order to facilitate the robustness to the degraded modalities, we employ the gated information fusion (GIF) network which weights the contribution from each modality according to the input feature maps to be fused. The weights are determined through the convolutional layers followed by a sigmoid function and trained along with the information fusion network in an end-to-end fashion. Our experiments show that the proposed GIF network offers the additional architectural flexibility to achieve robust performance in handling some degraded modalities, and show a significant performance improvement based on Single Shot Detector (SSD) for KITTI dataset using the proposed fusion network and data augmentation schemes.

##### Abstract (translated by Google)
多模态学习的目标是使用由多种模态提供的相关任务的补充信息来实现可靠和稳健的性能。最近，通过允许中间特征级别的信息融合，深度学习已经导致多模态学习的显着改进。本文讨论了在存在不完善模态的情况下设计鲁棒深度多模态学习架构的问题。我们引入了用于对象检测的深度融合架构，其使用单独的卷积神经网络（CNN）处理每个模态，并通过组合来自CNN的中间特征来构建联合特征图。为了便于降级模态的鲁棒性，我们采用门控信息融合（GIF）网络，根据要融合的输入特征图对每种模态的贡献进行加权。通过卷积层确定权重，然后是S形函数，并以端到端的方式与信息融合网络一起训练。我们的实验表明，所提出的GIF网络提供了额外的架构灵活性，可以在处理某些降级模式时实现稳健的性能，并且使用所提出的融合网络和数据增强方案，基于单镜头检测器（SSD）为KITTI数据集显示出显着的性能改进。

##### URL
[http://arxiv.org/abs/1807.06233](http://arxiv.org/abs/1807.06233)

##### PDF
[http://arxiv.org/pdf/1807.06233](http://arxiv.org/pdf/1807.06233)

