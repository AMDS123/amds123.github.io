---
layout: post
title: "Gated Feedback Refinement Network for Coarse-to-Fine Dense Semantic Image Labeling"
date: 2018-06-29 04:55:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Prediction
author: Md Amirul Islam, Mrigank Rochan, Shujon Naha, Neil D. B. Bruce, Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Effective integration of local and global contextual information is crucial for semantic segmentation and dense image labeling. We develop two encoder-decoder based deep learning architectures to address this problem. We first propose a network architecture called Label Refinement Network (LRN) that predicts segmentation labels in a coarse-to-fine fashion at several spatial resolutions. In this network, we also define loss functions at several stages to provide supervision at different stages of training. However, there are limits to the quality of refinement possible if ambiguous information is passed forward. In order to address this issue, we also propose Gated Feedback Refinement Network (G-FRNet) that addresses this limitation. Initially, G-FRNet makes a coarse-grained prediction which it progressively refines to recover details by effectively integrating local and global contextual information during the refinement stages. This is achieved by gate units proposed in this work, that control information passed forward in order to resolve the ambiguity. Experiments were conducted on four challenging dense labeling datasets (CamVid, PASCAL VOC 2012, Horse-Cow Parsing, PASCAL-Person-Part, and SUN-RGBD). G-FRNet achieves state-of-the-art semantic segmentation results on the CamVid and Horse-Cow Parsing datasets and produces results competitive with the best performing approaches that appear in the literature for the other three datasets.

##### Abstract (translated by Google)
本地和全局情境信息的有效整合对于语义分割和密集图像标记至关重要。我们开发两种基于编解码器的深度学习体系结构来解决这个问题。我们首先提出一种叫做标签细化网络（LRN）的网络架构，它以几种空间分辨率以粗到细的方式预测分割标签。在这个网络中，我们还定义了几个阶段的损失函数，以提供不同训练阶段的监督。但是，如果向前传递不明确的信息，则有可能限制提炼的质量。为了解决这个问题，我们还提出了解决这个限制的门控反馈细化网络（G-FRNet）。最初，G-FRNet进行粗粒度预测，通过在细化阶段有效整合本地和全球上下文信息，G-FRNet逐步细化以恢复细节。这是通过本工作中提出的门单元实现的，即控制信息向前传递以解决模糊性。在四个具有挑战性的稠密标记数据集（CamVid，PASCAL VOC 2012，Horse-Cow Parsing，PASCAL-Person-Part和SUN-RGBD）上进行实验。 G-FRNet在CamVid和Horse-Cow Parsing数据集上实现了最先进的语义分割结果，并产生了与文献中出现的其他三种数据集中表现最佳的方法相媲美的结果。

##### URL
[http://arxiv.org/abs/1806.11266](http://arxiv.org/abs/1806.11266)

##### PDF
[http://arxiv.org/pdf/1806.11266](http://arxiv.org/pdf/1806.11266)

