---
layout: post
title: "Efficient and Deep Person Re-Identification using Multi-Level Similarity"
date: 2018-03-30 06:18:28
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification CNN
author: Yiluan Guo, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Person Re-Identification (ReID) requires comparing two images of person captured under different conditions. Existing work based on neural networks often computes the similarity of feature maps from one single convolutional layer. In this work, we propose an efficient, end-to-end fully convolutional Siamese network that computes the similarities at multiple levels. We demonstrate that multi-level similarity can improve the accuracy considerably using low-complexity network structures in ReID problem. Specifically, first, we use several convolutional layers to extract the features of two input images. Then, we propose Convolution Similarity Network to compute the similarity score maps for the inputs. We use spatial transformer networks (STNs) to determine spatial attention. We propose to apply efficient depth-wise convolution to compute the similarity. The proposed Convolution Similarity Networks can be inserted into different convolutional layers to extract visual similarities at different levels. Furthermore, we use an improved ranking loss to further improve the performance. Our work is the first to propose to compute visual similarities at low, middle and high levels for ReID. With extensive experiments and analysis, we demonstrate that our system, compact yet effective, can achieve competitive results with much smaller model size and computational complexity.

##### Abstract (translated by Google)
人员重新识别（ReID）要求比较在不同条件下拍摄的人员的两幅图像。基于神经网络的现有工作通常计算单个卷积层的特征映射的相似性。在这项工作中，我们提出了一个高效的端到端完全卷积连体网络，计算多个层次的相似度。我们证明多级相似性可以在ReID问题中使用低复杂度的网络结构大大提高准确性。具体来说，首先，我们使用几个卷积层来提取两个输入图像的特征。然后，我们提出卷积相似网络来计算输入的相似度分数图。我们使用空间变换网络（STN）来确定空间关注。我们建议应用高效深度卷积来计算相似度。所提出的卷积相似性网络可以被插入不同的卷积层以提取不同级别的视觉相似性。此外，我们使用改进的排名损失来进一步提高性能。我们的工作是首次提出计算ReID的低，中，高级视觉相似度。通过广泛的实验和分析，我们证明我们的系统紧凑而有效，可以通过更小的模型尺寸和计算复杂性来实现竞争结果。

##### URL
[https://arxiv.org/abs/1803.11353](https://arxiv.org/abs/1803.11353)

##### PDF
[https://arxiv.org/pdf/1803.11353](https://arxiv.org/pdf/1803.11353)

