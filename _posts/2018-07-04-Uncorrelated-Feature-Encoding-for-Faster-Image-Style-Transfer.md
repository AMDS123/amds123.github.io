---
layout: post
title: "Uncorrelated Feature Encoding for Faster Image Style Transfer"
date: 2018-07-04 09:21:19
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Image_Classification Classification Relation
author: Minseong Kim, Jongju Shin, Myung-Cheol Roh, Hyun-Chul Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent fast style transfer methods use a pre-trained convolutional neural network as a feature encoder and a perceptual loss network. Although the pre-trained network is used to generate responses of receptive fields effective for representing style and content of image, it is not optimized for image style transfer but rather for image classification. Furthermore, it also requires a time-consuming and correlation-considering feature alignment process for image style transfer because of its inter-channel correlation. In this paper, we propose an end-to-end learning method which optimizes an encoder/decoder network for the purpose of style transfer as well as relieves the feature alignment complexity from considering inter-channel correlation. We used uncorrelation loss, i.e., the total correlation coefficient between the responses of different encoder channels, with style and content losses for training style transfer network. This makes the encoder network to be trained to generate inter-channel uncorrelated features and to be optimized for the task of image style transfer which maintained the quality of image style only with a light-weighted and correlation-unaware feature alignment process. Moreover, our method drastically reduced redundant channels of the encoded feature and this resulted in the efficient size of structure of network and faster forward processing speed. Our method can also be applied to cascade network scheme for multiple scaled style transferring and allows user-control of style strength by using a content-style trade-off parameter.

##### Abstract (translated by Google)
最近的快速风格转移方法使用预先训练的卷积神经网络作为特征编码器和感知损失网络。尽管预训练网络用于生成有效表示图像的样式和内容的感受域的响应，但是它不是针对图像样式转移而是针对图像分类进行优化。此外，由于其信道间相关性，它还需要耗时且考虑相关性的特征对准处理以用于图像样式传送。在本文中，我们提出了一种端到端学习方法，该方法优化了编码器/解码器网络以用于样式传送，并且减轻了特征对齐复杂度以考虑信道间相关性。我们使用不相关损失，即不同编码器信道的响应之间的总相关系数，以及训练风格转移网络的样式和内容损失。这使得编码器网络被训练以生成通道间不相关的特征并且针对图像样式转移的任务进行优化，其仅通过轻量且相关 - 不知道的特征对准过程来维持图像样式的质量。此外，我们的方法大大减少了编码特征的冗余信道，这导致了网络结构的有效尺寸和更快的前向处理速度。我们的方法也可以应用于多级缩放样式传输的级联网络方案，并允许用户通过使用内容式权衡参数来控制样式强度。

##### URL
[http://arxiv.org/abs/1807.01493](http://arxiv.org/abs/1807.01493)

##### PDF
[http://arxiv.org/pdf/1807.01493](http://arxiv.org/pdf/1807.01493)

