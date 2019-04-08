---
layout: post
title: "Relation-Aware Global Attention"
date: 2019-04-05 11:31:37
categories: arXiv_CV
tags: arXiv_CV Re-identification Segmentation Attention Person_Re-identification CNN Image_Classification Classification Relation
author: Zhizheng Zhang, Cuiling Lan, Wenjun Zeng, Xin Jin, Zhibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanism aims to increase the representation power by focusing on important features and suppressing unnecessary ones. For convolutional neural networks (CNNs), attention is typically learned with local convolutions, which ignores the global information and the hidden relation. How to efficiently exploit the long-range context to globally learn attention is underexplored. In this paper, we propose an effective Relation-Aware Global Attention (RGA) module for CNNs to fully exploit the global correlations to infer the attention. Specifically, when computing the attention at a feature position, in order to grasp information of global scope, we propose to stack the relations, i.e., its pairwise correlations/affinities with all the feature positions, and the feature itself together for learning the attention with convolutional operations. Given an intermediate feature map, we have validated the effectiveness of this design across both the spatial and channel dimensions. When applied to the task of person re-identification, our model achieves the state-of-the-art performance. Extensive ablation studies demonstrate that our RGA can significantly enhance the feature representation power. We further demonstrate the general applicability of RGA to vision tasks by applying it to the scene segmentation and image classification tasks resulting in consistent performance improvement.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02998](https://arxiv.org/abs/1904.02998)

##### PDF
[https://arxiv.org/pdf/1904.02998](https://arxiv.org/pdf/1904.02998)

