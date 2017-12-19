---
layout: post
title: "Learning Deep Representations of Appearance and Motion for Anomalous Event Detection"
date: 2015-10-06 12:42:55
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Dan Xu, Elisa Ricci, Yan Yan, Jingkuan Song, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel unsupervised deep learning framework for anomalous event detection in complex video scenes. While most existing works merely use hand-crafted appearance and motion features, we propose Appearance and Motion DeepNet (AMDN) which utilizes deep neural networks to automatically learn feature representations. To exploit the complementary information of both appearance and motion patterns, we introduce a novel double fusion framework, combining both the benefits of traditional early fusion and late fusion strategies. Specifically, stacked denoising autoencoders are proposed to separately learn both appearance and motion features as well as a joint representation (early fusion). Based on the learned representations, multiple one-class SVM models are used to predict the anomaly scores of each input, which are then integrated with a late fusion strategy for final anomaly detection. We evaluate the proposed method on two publicly available video surveillance datasets, showing competitive performance with respect to state of the art approaches.

##### Abstract (translated by Google)
我们提出了一个新的无监督深度学习框架异常事件检测复杂的视频场景。虽然大多数现有的作品仅仅使用手工制作的外观和运动特征，但我们提出了使用深度神经网络自动学习特征表示的外观和运动DeepNet（AMDN）。为了利用外观和运动模式的互补信息，我们引入了一种新型的双融合框架，结合了传统早期融合和后期融合策略的优点。具体而言，提出了叠层去噪自动编码器，以单独学习外观和运动特征以及联合表示（早期融合）。基于学习表示，使用多个单类SVM模型来预测每个输入的异常分数，然后将其与晚期融合策略整合以用于最终的异常检测。我们在两个公开可用的视频监控数据集上评估所提出的方法，显示了与最先进的方法相比的竞争性表现。

##### URL
[https://arxiv.org/abs/1510.01553](https://arxiv.org/abs/1510.01553)

##### PDF
[https://arxiv.org/pdf/1510.01553](https://arxiv.org/pdf/1510.01553)

