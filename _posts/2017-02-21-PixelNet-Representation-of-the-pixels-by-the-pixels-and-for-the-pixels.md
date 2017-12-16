---
layout: post
title: "PixelNet: Representation of the pixels, by the pixels, and for the pixels"
date: 2017-02-21 18:20:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation Prediction Detection
author: Aayush Bansal, Xinlei Chen, Bryan Russell, Abhinav Gupta, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We explore design principles for general pixel-level prediction problems, from low-level edge detection to mid-level surface normal estimation to high-level semantic segmentation. Convolutional predictors, such as the fully-convolutional network (FCN), have achieved remarkable success by exploiting the spatial redundancy of neighboring pixels through convolutional processing. Though computationally efficient, we point out that such approaches are not statistically efficient during learning precisely because spatial redundancy limits the information learned from neighboring pixels. We demonstrate that stratified sampling of pixels allows one to (1) add diversity during batch updates, speeding up learning; (2) explore complex nonlinear predictors, improving accuracy; and (3) efficiently train state-of-the-art models tabula rasa (i.e., "from scratch") for diverse pixel-labeling tasks. Our single architecture produces state-of-the-art results for semantic segmentation on PASCAL-Context dataset, surface normal estimation on NYUDv2 depth dataset, and edge detection on BSDS.

##### Abstract (translated by Google)
我们研究了从低级边缘检测到中级表面法线估计到高级语义分割的一般像素级预测问题的设计原则。卷积预测器，例如完全卷积网络（FCN），通过卷积处理利用相邻像素的空间冗余，取得了显着的成功。尽管计算效率很高，但我们指出，这种方法在学习期间不具有统计效率，因为空间冗余限制了从相邻像素学习的信息。我们证明像素的分层采样允许（1）在批量更新期间添加多样性，加速学习; （2）探索复杂的非线性预测因子，提高精度;和（3）针对不同的像素标记任务有效地训练最先进的模型白板（tabula rasa）（即“从头开始”）。我们的单一架构为PASCAL-Context数据集上的语义分割，NYUDv2深度数据集上的曲面法线估计以及BSDS上的边缘检测产生了最先进的结果。

##### URL
[https://arxiv.org/abs/1702.06506](https://arxiv.org/abs/1702.06506)

##### PDF
[https://arxiv.org/pdf/1702.06506](https://arxiv.org/pdf/1702.06506)

