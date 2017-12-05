---
layout: post
title:  'Feature Agglomeration Networks for Single Stage Face Detection'
date:   2017-12-05 19:45:13
categories: arXiv_CV
arXiv_CV 'Face Detection' 'Detection'
author: Jialiang Zhang, Xiongwei Wu, Jianke Zhu, Steven C.H. Hoi
---

* content
{:toc}

##### Abstract
Recent years have witnessed promising results of face detection using deep learning, especially for the family of region-based convolutional neural networks (R-CNN) methods and their variants. Despite making remarkable progresses, face detection in the wild remains an open research challenge especially when detecting faces at vastly different scales and characteristics. In this paper, we propose a novel framework of "Feature Agglomeration Networks" (FAN) to build a new single stage face detector, which not only achieves state-of-the-art performance but also runs efficiently. As inspired by the recent success of Feature Pyramid Networks (FPN) \cite{lin2016fpn} for generic object detection, the core idea of our framework is to exploit inherent multi-scale features of a single convolutional neural network to detect faces of varied scales and characteristics by aggregating higher-level semantic feature maps of different scales as contextual cues to augment lower-level feature maps via a hierarchical agglomeration manner at marginal extra computation cost. Unlike the existing FPN approach, we construct our FAN architecture using a new {\it Agglomerative Connection} module and further propose a {\it Hierarchical Loss} to effectively train the FAN model. We evaluate the proposed FAN detector on several public face detection benchmarks and achieved new state-of-the-art results with real-time detection speed on GPU.

##### Abstract (translated by Google)
近年来，使用深度学习的人脸检测已经取得了令人满意的结果，特别是对于基于区域的卷积神经网络（R-CNN）方法及其变体族。尽管取得了令人瞩目的进展，但在野外面部检测仍然是一个开放的研究挑战，尤其是在检测面部截然不同的尺寸和特征时。在本文中，我们提出了一种新的“特征聚集网络”（FAN）框架来构建一个新的单级人脸检测器，它不仅达到了最先进的性能，而且能够高效地运行。正如最近成功通过特征金字塔网络（FPN）引用通用对象检测的启发，我们框架的核心思想是利用单一卷积神经网络的固有多尺度特征来检测不同尺度通过将不同规模的高级语义特征地图作为上下文线索进行聚合，以边缘额外的计算代价，通过分层聚集方式来扩充底层特征地图。与现有的FPN方法不同，我们使用一个新的{\ it Agglomerative Connection}模块来构建我们的FAN体系结构，并进一步提出了一个有效训练FAN模型的分层丢失模型。我们在多个公共人脸检测基准上对所提出的FAN检测器进行评估，并在GPU上实现了具有实时检测速度的最新技术成果。

##### URL
[http://arxiv.org/abs/1712.00721](http://arxiv.org/abs/1712.00721)

