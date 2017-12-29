---
layout: post
title: "Learning Two-Branch Neural Networks for Image-Text Matching Tasks"
date: 2017-12-28 09:18:06
categories: arXiv_CV
tags: arXiv_CV Attention Embedding
author: Liwei Wang, Yin Li, Jing Huang, Svetlana Lazebnik
mathjax: true
---

* content
{:toc}

##### Abstract
Image-language matching tasks have recently attracted a lot of attention in the computer vision field. These tasks include image-sentence matching, i.e., given an image query, retrieving relevant sentences and vice versa, and region-phrase matching or visual grounding, i.e., matching a phrase to relevant regions. This paper investigates two-branch neural networks for learning the similarity between these two data modalities. We propose two network structures that produce different output representations. The first one, referred to as an embedding network, learns an explicit shared latent embedding space with a maximum-margin ranking loss and novel neighborhood constraints. Compared to standard triplet sampling, we perform improved neighborhood sampling that takes neighborhood information into consideration while constructing mini-batches. The second network structure, referred to as a similarity network, fuses the two branches via element-wise product and is trained with regression loss to directly predict a similarity score. Extensive experiments show that our networks achieve high accuracies for phrase localization on the Flickr30K Entities dataset and for bi-directional image-sentence retrieval on Flickr30K and MSCOCO datasets.

##### Abstract (translated by Google)
图像语言匹配任务近来在计算机视觉领域引起了很多关注。这些任务包括图像 - 句子匹配，即给定图像查询，检索相关句子，反之亦然，以及区域词组匹配或视觉基础，即将短语与相关区域相匹配。本文研究两分支神经网络来学习这两种数据模式之间的相似性。我们提出两种产生不同输出表示的网络结构。第一个被称为嵌入网络，学习一个具有最大边缘排序损失和新邻域约束的显式共享潜在嵌入空间。与标准三元组抽样相比，我们在构建小批量时，考虑邻域信息的情况下，进行改进的邻域抽样。被称为相似性网络的第二种网络结构通过基于元素的产品将两个分支融合在一起，并用回归损失进行训练以直接预测相似性分数。大量的实验表明，我们的网络在Flickr30K Entities数据集上获得了高精度的短语定位，并在Flickr30K和MSCOCO数据集上获得了双向图像 - 句子检索的精度。

##### URL
[http://arxiv.org/abs/1704.03470](http://arxiv.org/abs/1704.03470)

##### PDF
[http://arxiv.org/pdf/1704.03470](http://arxiv.org/pdf/1704.03470)

