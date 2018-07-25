---
layout: post
title: "Face Mask Extraction in Video Sequence"
date: 2018-07-24 16:09:32
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Face CNN RNN Relation
author: Yujiang Wang, Bingnan Luo, Jie Shen, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the recent development of deep network-based methods in semantic image segmentation, we introduce an end-to-end trainable model for face mask extraction in video sequence. Comparing to landmark-based sparse face shape representation, our method can produce the segmentation masks of individual facial components, which can better reflect their detailed shape variations. By integrating Convolutional LSTM (ConvLSTM) algorithm with Fully Convolutional Networks (FCN), our new ConvLSTM-FCN model works on a per-sequence basis and takes advantage of the temporal correlation in video clips. In addition, we also propose a novel loss function, called Segmentation Loss, to directly optimise the Intersection over Union (IoU) performances. In practice, to further increase segmentation accuracy, one primary model and two additional models were trained to focus on the face, eyes, and mouth regions, respectively. Our experiment shows the proposed method has achieved a 16.99% relative improvement (from 54.50% to 63.76% mean IoU) over the baseline FCN model on the 300 Videos in the Wild (300VW) dataset.

##### Abstract (translated by Google)
受到最近语义图像分割中基于深度网络的方法的发展的启发，我们引入了用于视频序列中的面罩提取的端到端可训练模型。与基于地标的稀疏人脸形状表示相比，我们的方法可以生成单个面部组件的分割掩模，可以更好地反映其详细的形状变化。通过将卷积LSTM（ConvLSTM）算法与完全卷积网络（FCN）集成，我们的新ConvLSTM-FCN模型基于每个序列工作，并利用视频剪辑中的时间相关性。此外，我们还提出了一种新的损失函数，称为分段损失，以直接优化联合交叉（IoU）性能。在实践中，为了进一步提高分割精度，分别训练一个主要模型和两个附加模型以集中于面部，眼睛和嘴部区域。我们的实验表明，在300个野外视频（300VW）数据集中，所提出的方法相对于基线FCN模型实现了16.99％的相对改善（从54.50％到63.76％平均IoU）。

##### URL
[https://arxiv.org/abs/1807.09207](https://arxiv.org/abs/1807.09207)

##### PDF
[https://arxiv.org/pdf/1807.09207](https://arxiv.org/pdf/1807.09207)

