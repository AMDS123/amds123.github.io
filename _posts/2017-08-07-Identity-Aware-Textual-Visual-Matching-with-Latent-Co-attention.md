---
layout: post
title: "Identity-Aware Textual-Visual Matching with Latent Co-attention"
date: 2017-08-07 04:57:45
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Shuang Li, Tong Xiao, Hongsheng Li, Wei Yang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Textual-visual matching aims at measuring similarities between sentence descriptions and images. Most existing methods tackle this problem without effectively utilizing identity-level annotations. In this paper, we propose an identity-aware two-stage framework for the textual-visual matching problem. Our stage-1 CNN-LSTM network learns to embed cross-modal features with a novel Cross-Modal Cross-Entropy (CMCE) loss. The stage-1 network is able to efficiently screen easy incorrect matchings and also provide initial training point for the stage-2 training. The stage-2 CNN-LSTM network refines the matching results with a latent co-attention mechanism. The spatial attention relates each word with corresponding image regions while the latent semantic attention aligns different sentence structures to make the matching results more robust to sentence structure variations. Extensive experiments on three datasets with identity-level annotations show that our framework outperforms state-of-the-art approaches by large margins.

##### Abstract (translated by Google)
文本 - 视觉匹配旨在测量句子描述和图像之间的相似性。大多数现有的方法在解决这个问题时没有有效地利用身份级别的注释。在本文中，我们提出了一个用于文本 - 视觉匹配问题的身份感知两阶段框架。我们的第一阶段CNN-LSTM网络学习了跨模态特征嵌入一个新的横模交叉熵（CMCE）损失。第一阶段网络能够有效地筛选容易出现错误的配对，并为第二阶段训练提供初始训练点。第二阶段CNN-LSTM网络利用潜在的共同关注机制来提炼匹配结果。空间注意力将每个单词与相应的图像区域相关联，而潜在的语义注意力将不同的句子结构对齐，以使得匹配结果对于句子结构变化更稳健。在三个具有身份级别注释的数据集上进行的大量实验表明，我们的框架在性能上优于最先进的方法。

##### URL
[https://arxiv.org/abs/1708.01988](https://arxiv.org/abs/1708.01988)

##### PDF
[https://arxiv.org/pdf/1708.01988](https://arxiv.org/pdf/1708.01988)

