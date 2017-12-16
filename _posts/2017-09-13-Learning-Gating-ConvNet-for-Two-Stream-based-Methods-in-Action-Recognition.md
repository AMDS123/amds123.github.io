---
layout: post
title: "Learning Gating ConvNet for Two-Stream based Methods in Action Recognition"
date: 2017-09-13 09:13:31
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Prediction Recognition
author: Jiagang Zhu, Wei Zou, Zheng Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
For the two-stream style methods in action recognition, fusing the two streams' predictions is always by the weighted averaging scheme. This fusion method with fixed weights lacks of pertinence to different action videos and always needs trial and error on the validation set. In order to enhance the adaptability of two-stream ConvNets and improve its performance, an end-to-end trainable gated fusion method, namely gating ConvNet, for the two-stream ConvNets is proposed in this paper based on the MoE (Mixture of Experts) theory. The gating ConvNet takes the combination of feature maps from the same layer of the spatial and the temporal nets as input and adopts ReLU (Rectified Linear Unit) as the gating output activation function. To reduce the over-fitting of gating ConvNet caused by the redundancy of parameters, a new multi-task learning method is designed, which jointly learns the gating fusion weights for the two streams and learns the gating ConvNet for action classification. With our gated fusion method and multi-task learning approach, a high accuracy of 94.5% is achieved on the dataset UCF101.

##### Abstract (translated by Google)
对于动作识别中的双流式方法，融合两个流的预测总是通过加权平均方案。这种具有固定权重的融合方法对于不同的动作视频缺乏针对性，总是需要对验证集进行反复试验。为了增强双流ConvNet的适应性，提高其性能，本文提出了一种端到端可训练的门控融合方法ConvNet， ）理论。门控ConvNet采用空间网络和时间网络同层的特征映射作为输入，并采用ReLU（整流线性单元）作为门控输出激活函数。为了减少参数冗余引起的门控ConvNet的过度拟合问题，设计了一种新的多任务学习方法，共同学习两个流的门控融合权值，学习门控ConvNet进行动作分类。使用门控融合方法和多任务学习方法，在数据集UCF101上实现了94.5％的高精度。

##### URL
[https://arxiv.org/abs/1709.03655](https://arxiv.org/abs/1709.03655)

##### PDF
[https://arxiv.org/pdf/1709.03655](https://arxiv.org/pdf/1709.03655)

